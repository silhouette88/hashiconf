# Hashiconf 18 Takeaways

### Keynote
On Tuesday the first Keynote presentation was mostly about changes to Hashicorp's core products: Terraform, Vault, Consul, and Nomad. Most of the subsequent talks were aimed around those products. There were over 1,200 people in attendance this year, which I think is a nice balance. It didn't feel overly crowded and we were able to have some conversations with other attendees during lunch and breaks. Some of the talks were good, some were lacking, but all in all it was put together well and probably means that the next conference will be even larger. It sounds like the next one will be in Seattle!

There were keynote presentations from AWS and Google, and a talk by Brendan Burns (co-founder of Kubernetes, now at Microsoft). I feel Hashicorp did a good job with staying neutral and giving equal amounts of exposure to the Big Three cloud providers. They said that they plan on posting all of the Keynotes and talks on YouTube in a few weeks.

We missed Training Day which happened on Monday. It would have been nice to attend the training sessions to be able to ask questions and also hear questions from others to learn about what people are doing with Hashicorp products "in the wild". They do have (paid) [online training](https://www.hashicorp.com/training) sessions. I attended one for Vault last year and found the material only somewhat useful (they seemed targeted to brand new users), but again the questions from the other trainees were valuable.

### Learning Platform
They launched a [learning portal](https://www.hashicorp.com/blog/hashicorp-learn-platform-with-vault) ahead of the conference and they talked a bit about that. Vault is the only product they currently have training material on, but they say they are trying to finish up the other three core products in Q4. I checked the Vault one out and it's well done. They have [learning tracks](https://learn.hashicorp.com/) for beginner, intermediate, and advanced users. Prior to this you had to spend a lot of time searching through their documentation to figure out what you need, so this is a welcome change to have everything curated for you.

### Nomad
The talks about [Nomad](https://www.nomadproject.io/) were the ones both @therubymug and I really wanted to hear. There was a good overview talk, and one on upcoming changes in 0.9. When we were waiting for our plane back home we hacked on Nomad a bit and it was very easy to spin up a Nomad cluster in local development with zero configuration. All that was needed was a running Consul "server" agent, and then Nomad automatically registered itself into Consul. The Nomad UI is very easy to use. They seemed to have spent a lot of time recently on making sure the UI aligns with the product's CLI and API features. We found out that they have over 300 employees now, up from 70 in the beginning of 2017. 75 are sales, but they mainly added engineers to support the development of their four core products.

### Other Announcements
[Atlantis was purchased by Hashicorp](https://medium.com/runatlantis/joining-hashicorp-200ee9572dc5), their first acquisition (I think). Neither @therubymug nor I had any experience with Atlantis, but it seems like it's a system that does what our current workflow already does (Github PR -> peer review -> terraform plan -> terraform apply). I think the only thing that seems better is that they make the `terraform plan` more visible and collaborative. The way we do it, someone needs to click over to the CircleCI workflow and verify the plan. 

However Hashicorp did announce that they were [opening up their collaborative features to all users](https://www.hashicorp.com/blog/terraform-collaboration-for-everyone) (previously an Enterprise only thing). Again, most of this stuff (such as remote state storage) we've been using for awhile. But it's nice to do things in a more "official" way, so we're learning from the collective mind and taking advantage of people's trials and errors. Also, it's really nice to see Hashicorp continuing to give back to their users / early supporters.

They announced a few things related to K8S that seemed to be well-received, but I think most of the attendees were probably current (or future) Nomad users (based on zero scientific research).

### External Resources
* [Terraform 0.12 Preview](https://www.hashicorp.com/blog/terraform-0-1-2-preview)
* [Terraform 0.12 First Class Expressions](https://www.hashicorp.com/blog/terraform-0-12-preview-first-class-expressions)
* [Terraform 0.12 For Loops](https://www.hashicorp.com/blog/hashicorp-terraform-0-12-preview-for-and-for-each)
* [Terraform 0.12 Generalized Splat Operator](https://www.hashicorp.com/blog/terraform-0-12-generalized-splat-operator)
* [Terraform 0.12 Rich Value Types](https://www.hashicorp.com/blog/terraform-0-12-rich-value-types)
* [Terraform 0.12 Template Syntax](https://www.hashicorp.com/blog/terraform-0-12-template-syntax)
* [Terraform 0.12 Reliable JSON Syntax](https://www.hashicorp.com/blog/terraform-0-12-reliable-json-syntax)
* [Using Consul at Some Scale](https://ashald.net/using-consul-at-some-scale/)
* [Infrastructure Lessons Learned](https://www.slideshare.net/brikis98/lessons-learned-from-writing-over-300000-lines-of-infrastructure-code-120597849)
* [You Must Build a Raft](https://catonacomputer.com/slides/youmustbuildaraft.pdf)

### Fun Stuff
* [Spotify Playlist](https://open.spotify.com/playlist/0GFOgzVhXdugWCu1es32ni)

> Written with [StackEdit](https://stackedit.io/).
