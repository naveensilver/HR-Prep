## HR-Prep

### About Southwest Airlines:

Southwest is one of the largest low-cost airlines in the US — known for its customer-first approach and point-to-point operating model, which helps reduce delays and keep costs under control.

Their three values really connected with me personally:

- **Warrior Spirit** — because in DevOps, when production breaks at 2am, you don't wait for someone else — you fix it.  
- **Servant's Heart** — because it's not just about fixing things, it's about helping your team understand *why* it broke.  
- **Fun-LUVing Attitude** — because even in stressful situations, staying calm and positive makes the whole team work better.

From a technology perspective, the business depends on reliable real-time systems like bookings, flight operations, and customer communication. Even a small downtime directly impacts revenue and customer experience.

So from a DevOps perspective, the focus here is not just on deployments — it's about building highly available, stable, and cost-efficient systems.

And that's exactly the kind of work I've been doing and want to go deeper into.


### Self-Intro-SWA

My name is Naveen, and I'm a DevOps Engineer with around 4 years of experience working on cloud infrastructure, primarily on AWS.

I've been focusing on building and optimizing CI/CD pipelines, automating infrastructure using Terraform, and managing containerized applications on Kubernetes.

In my recent project, I improved deployment efficiency by reducing release time by around 50% by redesigning the pipeline and streamlining the process. I also worked on AWS cost optimization by identifying unused resources and tuning services like Lambda, which helped reduce overall cloud costs.

Along with that, I've handled production issues where I focused on quick troubleshooting and minimizing downtime by following a structured approach.

Now, I'm looking for an opportunity where I can take more ownership of production systems and contribute to building reliable, scalable, and cost-efficient platforms — and Southwest feels like exactly the right place for that.

### 🎤 About TCS

TCS is one of the largest IT services companies in the world and part of the Tata Group.

It works with clients across different industries like banking, telecom, retail, and more, providing IT services, consulting, and software development.

What I like about TCS is its strong structured environment. It has very well-defined processes, which helps build discipline and a strong foundation for anyone starting their career in IT.

It’s a place where you learn how large enterprise systems work and how to work in a professional, process-driven environment.

### 🎤 About My Experience at TCS

I started my career at TCS, where I got a strong foundation in IT and DevOps basics.

I worked on cloud and infrastructure-related tasks where I got exposure to AWS services, basic CI/CD pipelines, and production support activities.

The main thing I learned at TCS was discipline in processes — how enterprise systems work, how tickets are handled, and how important stability and documentation are in large-scale environments.

It helped me build a strong base before moving into more hands-on DevOps work later.

## 🎤 About CGI

CGI is also a global IT and consulting company that provides services like cloud solutions, application development, and infrastructure management.

They work closely with clients on digital transformation, DevOps, and managed services.

What I like about CGI is the focus on end-to-end delivery and real production systems. Teams often get hands-on exposure to cloud, automation, and support of live applications.

It’s a place where you get more technical ownership compared to very traditional service environments.

## 🎤 About My Experience at CGI

At CGI, I moved more into hands-on DevOps work.

I worked mainly on AWS infrastructure, Terraform, and Kubernetes-based deployments.

This is where I got real production exposure — building pipelines, automating deployments, and supporting live systems. I also handled production issues where quick troubleshooting and root cause analysis were important.

I also worked on improvements like reducing deployment time, optimizing Docker images, and helping reduce cloud costs by identifying unused resources.

Overall, CGI helped me grow from basic DevOps understanding to actually working on real production systems and taking ownership of issues.

### "Why Southwest?" 

Honestly, a few things stood out to me.

First — Southwest is not just another IT company. It's an airline where systems have to work all the time. Bookings, flight operations, and customer communication — if something breaks, it directly impacts real people and real revenue. That kind of high-accountability environment is where I want to work.

Second — their culture: **Warrior Spirit, Servant's Heart, Fun-LUVing Attitude**. These connected with me personally because that's honestly how I already approach my work — ownership, helping the team, and staying calm under pressure.

And third — they have a strong tech center right here in Hyderabad. So it's not just a support office; real technology decisions are being made here. That means real growth opportunities for me.

### What motivates you in your work?

I’m mainly motivated by solving real problems and seeing the impact of my work in production.

For example, when I optimize a pipeline or fix an issue that improves system performance or reduces downtime, it gives me a lot of satisfaction.

I also enjoy learning new things and improving existing systems to make them more efficient and reliable.


### "Why Are You Leaving?" — Final Answer

My recent project ended — it was a cost optimization decision from the client side, and the team got restructured. It had nothing to do with performance, it was purely a business decision.

After that, I explored internal opportunities within CGI, but nothing matched what I’m looking for right now.

So I decided to use this time to find a long-term opportunity — where I can settle, contribute, and grow for several years, rather than moving into another short-term project.

That’s what brought me here. Southwest feels like that place.

### 🎤 "Are you on bench or serving notice?" — Your Answer

I'm currently on the bench at CGI. I've already discussed this with my HR, and they are okay to release me early once I have a confirmed offer.

So there won’t be any delay from my side — I can join pretty quickly once things are finalized.

### Salary Expectation — Answer

I'm not looking at it based on my current salary. I'm looking at what the market pays for someone with hands-on experience in AWS, Kubernetes, Terraform, and CI/CD.

Based on my research, that range is around 15 to 17 LPA in Hyderabad for this kind of profile.

That said, I'm also open to understanding what Southwest has budgeted — because I'm genuinely interested in this opportunity, not just the number.

### Production Issue — Example Answer

This happened at CGI during a production deployment.

We pushed a release, and shortly after, alerts started coming in — the server was running out of memory and performance was degrading. Real users were getting affected.

My team lead was not available, so I took ownership of the situation.

I went straight to the logs, checked the running containers, and identified that one of the newly deployed containers had no memory limits set. Because of that, it kept consuming memory until the server was overwhelmed.

I quickly fixed the resource limits, restarted the affected pods, and the system stabilized. The whole process took around 45 minutes.

After resolving the issue, I documented a proper RCA and added resource limit validation as a standard step in our deployment checklist to prevent this from happening again.

This experience taught me that a deployment isn’t complete just because the pipeline is green — you need to actively monitor what happens after the release as well.


### "Tell me about a time you showed ownership" — Your Answer

This was something I noticed on my own — nobody asked me to fix it.

We had Dockerfiles set up for our application, and the image sizes were quite large. Because of that, our CI/CD pipelines were taking longer to build and deploy. It was slowing down the whole team, but everyone had started accepting it as normal.

I felt this was something I could improve, so I took ownership without waiting for it to be assigned.

I reworked the Dockerfiles using multi-stage builds — separating the build stage from the final image so that only the necessary components go into the final container. I also switched to distroless base images, which avoid unnecessary packages and tools.

As a result, the image size reduced significantly, and our pipelines became noticeably faster. Additionally, removing unnecessary packages improved the overall security posture by reducing the attack surface.

What I liked about this experience is that it wasn’t part of my assigned work — I identified a problem, understood its impact, and took the initiative to fix it. That’s how I approach ownership.

### Career Goals — Answer

I want to grow into a Cloud Architect role in the next 3 to 5 years.

Right now, I have strong hands-on experience with AWS, Kubernetes, Terraform, and CI/CD. But I want to go beyond implementation — I want to design infrastructure, make architectural decisions, and think about scale, cost, and security from the ground up.

Also, with how the industry is evolving, AI is becoming a big part of infrastructure and DevOps. Things like AI-powered monitoring, intelligent auto-scaling, and AIOps are already happening. I want to build skills in how AI integrates with cloud architecture and DevOps workflows.

I believe this kind of growth comes from staying in an environment where you can see the full picture and take on increasing responsibility. Southwest feels like the right place for that — strong tech presence in Hyderabad, meaningful work, and real exposure.

My goal is simple — to contribute effectively, grow with the team, and over time become someone who designs intelligent cloud systems, not just builds them.

### AI Experience — Answer

Yes — I haven’t used AI tools heavily in production yet, but I did build a small project around it.

The idea was simple: developers often struggle with writing good Dockerfiles. So I integrated the Google Gemini API into a tool where a developer can provide their application code, and it automatically generates a Dockerfile.

I designed the prompts carefully so the AI doesn’t just generate any Dockerfile — it produces one that is optimized, secure, and follows best practices like multi-stage builds and minimal base images.

It was a small project, but it helped me understand how AI can actually save real time in DevOps workflows.

That’s the direction I want to grow in — using AI not just as a chatbot, but as a practical tool inside real engineering systems and workflows.

### AI in DevOps — Answer

AI is already changing DevOps, and it's only going to grow further.

Right now, we manually monitor systems, write pipelines, and debug failures. AI is gradually taking over the repetitive parts of this work — like detecting anomalies before they become incidents, suggesting fixes, and even generating code and configurations automatically.

Areas like AIOps, AI-powered monitoring, and auto-healing systems are becoming real now — not just future concepts.

On a personal level, I’ve already explored this by building a small tool that uses AI to generate Dockerfiles automatically. It gave me a clear idea of how much time AI can save in real workflows.

In the next few years, I believe the best DevOps engineers won’t be the ones who resist AI — but the ones who know how to use it effectively inside their workflows.

### "Tell me about a mistake you made/Conflicts with teammate"

This happened during a regular working day.

My teammate raised a PR and asked me to review and merge it. I was about to approve it, and at the same time, he found an issue in his own code and quickly messaged me asking not to merge yet.

But I had already merged it before I saw his message. That broke the pipeline, and we had to roll it back.

There was a moment of tension — he was frustrated, and honestly I felt bad too.

I went to him directly and said, “My bad — I should have double-checked before merging. Let’s fix it together.”

We rolled it back, he fixed the issue, and we redeployed.

After that, we introduced a simple rule: for urgent PR updates, we always do a quick direct ping before merging, not just a message that can be missed.

There were no hard feelings after that — we actually laughed about it later.

### "Tell me about a conflict with a manager" — Answer

This happened during an infrastructure migration task.

My manager gave me a deadline that I felt was a bit too tight for the amount of work involved. Migration work needs proper testing, validation, and rollback planning, so rushing it could create risk.

I did raise my concern once and explained that the timeline might be tight and could affect quality. But due to business pressure, the deadline stayed the same.

After that, I focused on delivering it as best as I could. I worked extra hours and prioritized the critical parts, but even then, I missed the deadline by a couple of days because I didn’t want to skip testing or cut corners.

When I informed my manager, I was honest about it. I explained what was completed, what was still pending, and shared a clear plan to finish it.

He was initially not very happy, but he appreciated the transparency and the fact that I had a proper plan in place. We completed the migration shortly after, and everything went smoothly in production.

Looking back, I feel I should have backed my concern with more details instead of just saying the timeline is tight. Now, whenever I see a deadline, I break down the work properly and communicate realistic timelines with clear reasoning.

### 🎤 "Tell me about a time you learned something new quickly" — Answer

Note: Talk about security tools like Trivy - integration with Jenkins

When I moved to a new project, the team was using Terraform for infrastructure provisioning. I had heard about it before, but I had never worked on it hands-on.

The project required me to start contributing quickly, so I didn’t have much time for a long learning phase.

I started learning it in parallel with work — I watched tutorials in the evenings and understood the basics like providers, state files, and modules. During the day, I applied whatever I learned directly in the project.

Within a few weeks, I started writing Terraform code on my own — creating AWS resources, managing state, and building reusable modules.

What I learned from this experience is that the fastest way to learn DevOps tools is by using them in real work. Tutorials help you get started, but real understanding comes when you actually use it and fix issues yourself.

Now, whenever I learn something new, I try to understand the basics quickly and then start applying it as soon as possible.

### "How do you handle pressure?" — Answer

I'll give you a real example.

We had a deployment go to production, and shortly after that, things started breaking. Users were getting impacted, and we quickly realized something in the release had gone wrong.

It was already evening, and most of the team had logged off. I stayed back because I knew it needed to be fixed before the next day.

I didn’t panic. I just took it step by step — checked the logs, looked at what changed in the deployment, and tried to identify the issue.

Once I found the root cause, I rolled back the deployment, made sure everything was stable, and then did a clean redeploy after fixing the issue.

It took a few hours, but production was stable by the end of it.

For me, pressure is part of DevOps. Things will break. The key is staying calm, thinking clearly, and fixing the problem step by step instead of rushing.
