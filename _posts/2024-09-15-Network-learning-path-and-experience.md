---
title : "Network learning path and experience"
date : 2024-09-15 19:00:00 +800
categories : [Path]
tags : [Path]
---

Hey everyone! 😊 Before I dive into my certification journey and how you can customize your own study plan, let me share a bit about myself. I’m currently a computer science undergraduate at Universiti Malaya, majoring in Computer System and Network. My university offers some amazing courses tailored for my major, including Network Technology Foundation, Advanced Network Technology, Enterprise Network Design and Management, and Programmable Network—all of which are built around Cisco NetAcad teaching materials. I followed this structured learning path and used it to build my computer networking skills from the ground up. While NetAcad is a great starting point for mastering the fundamentals, I’m a huge advocate of hands-on learning because it really accelerates skill development. Shout-out to the Advanced Network Technology and Enterprise Network courses at my university for emphasizing hands-on labs—they made a world of difference! 🙌 These courses, in my opinion, set me up well to become a capable associate network engineer.

# Learning the Fundamentals: The Hardest, Yet Most Rewarding Part 💡
Let’s be real—getting the fundamentals down is tough. But understanding the why behind problems and the how behind solutions is what really solidifies your learning. Take this example: layer 2 loops. They happen because there’s no detection method built into layer 2 frames (unlike layer 3 packets, which have TTL to prevent infinite loops). Enter the Spanning Tree Protocol (STP), our hero that saves the day with its unique calculation methods. But STP can be slow (I’ll spare you the details for now), which led to the introduction of Rapid Spanning Tree Protocol (RSTP), thanks to some process tweaks and new port roles. Even then, RSTP had its limitations, like not being able to balance traffic effectively, leading to the birth of Multiple Spanning Tree Protocol (MSTP)—a solution that groups VLANs and manages them collectively.

Understanding concepts through this problem-solving chain makes it way easier to grasp the logic and configuration behind them. Networking is notoriously vendor-specific, so when configuring different products, you might hit a few roadblocks. The trick? Learn the essential steps for configuring features instead of memorizing vendor-specific commands. For instance, before setting up trunk ports, you need to create the VLANs—this step is almost universal across different vendors. Sure, there are differences (e.g., CDP for Cisco versus LLDP for other brands), but the core principles are the same. Nowadays, everyone can copy-paste commands from documentation, so focus on understanding the process and memorizing only the crucial troubleshooting commands. 💻

# Tips I’ve Picked Up From the Pros 👨‍💻
My experiences aren’t just from books and courses—I’ve learned a lot by talking to experienced network engineers. Most of them share the same advice: learn beyond TCP/IP. Getting familiar with related fields like network automation, security and cloud technology will future-proof your career. It’s logical, and I think it’s worth sharing.

Another thing to note: being a network engineer isn’t always a 9-to-5 job. Sometimes, you’ll find yourself working overnight to avoid interrupting business operations. If that doesn’t sound appealing, consider a presales role, where you’ll be presenting and selling solutions instead of working on configurations. The upside? More predictable hours. 💼 As for the pay in Malaysia, it’s generally on par with software engineering salaries, plus some extra allowances. Want specifics? Just look up the companies you’re interested in and compare.

# My Go-To Study Resources 📚
If you’re aiming to learn networking fundamentals, Jeremy IT Lab on YouTube and the CCNA cert guide are golden. But don’t skip the hands-on practice—it’s essential if you want to be more than just book-smart. Jeremy’s CCNP ENCOR content is on the way, so keep an eye out for that as a future resource. For those diving into HCIP Advanced Routing & Switching, be aware there’s no official simulator anymore (eNSP). The course itself goes into deep technical detail, covering everything from deterministic routes to backup paths. If you want to keep your skills sharp with the latest tech, check out Cisco DevNet—it’s a fantastic platform for trying out their latest products for training purposes. Oh, and one more thing—taking vendor certifications can really boost your confidence in your networking skills. 🎓 Think CCNA, CCNP, and CCIE (or their equivalents from other vendors)(their learning material will really prepare you well). Most students should be able to tackle an associate-level certification after completing their university courses. And if you’re feeling ambitious, why not go for the professional-level certs? It’s totally doable with enough hard work and dedication. Plus, if you can pass the professional level, you might even save yourself RM500 by skipping the associate cert. 😉

And that’s a wrap on my current thoughts and experiences! I’m always learning, so if you spot something that could be improved, feel free to drop me an email. I’m still new to this field, but I hope my journey helps guide yours. Just remember, the world of networking is fundamental but ever-evolving—don’t be afraid to expand into virtualization and cloud tech as you grow. 🌱

Lastly, this is a graphical roadmap that i get from a github account that I think would be helpful(https://github.com/eovchar/neteng-roadmap/)

![alt text](/assets/img/network path/NetengRoadmap_v2.png)

Hope this helps, and happy studying! 🚀

**Above blog is generated with the help of GPT XD**