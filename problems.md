A list of things that we need to be able to achieve but don’t have the technical skills to achieve effectively. It’s something we can pull learning goals from and know that we’re solving real problems.

When adding a "problem", make sure to articulate what kind of task needs to be achieved. That way, when you take on a learning goal to achieve the problem, you'll have something concrete that you can bring up at reviews and say that you fixed.

-------------------
Add problems below:
-------------------

### Problem: Central management of users on servers
**Synopsis:** We can't effectively manage user accounts on all of the servers that we manage. When new staff join the team, we have to manually add their user and SSH key to each server. When staff leave, we often can't be bothered combing through every server to remove their access. And don't even think about refreshing everyone's security keys. We need a way to centrally and effectively manage user accounts on every server that we control.

### Problem: Transactional mail sending
**Synopsis:** Many of the websites that we host need to send transactional email, from contact form submissions to password resets to e-commerce order receipts. An SMTP service with good analytics helps us identify deliverability issues with minimal fuss. We have been happily using Mandrill for the last year or two for most of our clients. Mandrill is now removing their free tier and we must either pay for a central Manrill account or migrate clients elsewhere. One alternative is SendGrid.
