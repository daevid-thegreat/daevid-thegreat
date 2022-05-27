## Handling forms in a static site

Hey guys, I was working on my personal website when I reached an issue, **HOW TO SUBMIT MY MESSAGE FORM**.
My site was a static site, I didn't want to add a backend so as to not make my website heavier, so I researched and found this awesome website [Formspree](https://formspree.io/).
It was so easy to understand that I had my form working in barely 2 minutes.
## My form

```
<form action="https://formspree.io/f/{your_id}}" method="POST">
                <div class="row g-3">
                    <div class="col">
                      <input type="text" class="form-control" name="fullname" placeholder="Your Name" aria-label="Name">
                    </div>
                    <div class="col">
                      <input type="email" class="form-control" name="email" placeholder="Your Email" aria-label="Email">
                    </div>
                  <div class="mb-3">
                    <textarea class="form-control" id="exampleFormControlTextarea1" name="message" placeholder="Type your message here" rows="3"></textarea>
                  </div>
                </div>
                <button type="submit" class="btn btn-outline-dark col-12">Send Message</button>
            </form>
``` 
and when I tested it out I got my message sent to my Formspree dashboard and to my email.

## Message in my Formspree dashboard
![Formspree dashboard](https://cdn.hashnode.com/res/hashnode/image/upload/v1653676928145/Neo9tp2Al.png align="left")

## Message in my Gmail

![My Gmail](https://cdn.hashnode.com/res/hashnode/image/upload/v1653677144394/PqpZo6IAA.png align="left")

And as if all these aren't enough, they had a free plan that fits my personal website.
They also had 4 paid plans with even more features like creating a team, custom redirect, spam filtering, auto-responses, custom domain, and so on...
The paid plan starts from $8 per month to $85 per month and it even goes higher with more features in the custom plan.
You can check their pricing page to see for yourself [Formspree plans](https://formspree.io/plans)



Thanks for reading I hope you loved the article 😊.

You can follow me on Twitter at [@daevid_thegreat](https://twitter.com/Daevid_Thegreat)
