![Hop Onboard banner logo](https://cloud-b3h81o0df-hack-club-bot.vercel.app/0onboard_github.png)

# OnBoard - Get a $100 grant and make a PCB!

> "I’m so glad that young people can create things like PC boards online. May your creativity have no limits!”
>
> _– [Steve Wozniak](https://en.wikipedia.org/wiki/Steve_Wozniak), Apple co-founder_

It's easier than ever for high school students to get involved with programming; all you need is a computing device and internet access. Yet, *it's not the same for hardware*. While PCB fabs have greatly increased the accessibility for professionally done boards, there is still no clear way for high school students to jump in. This is where OnBoard comes in.

---

Every student will receive up to $100 to cover PCB manufacturing costs, and join a community of peers– some more beginner and some more experienced.

## Requirements

Every design/submission needs to meet the following constraints to be approved:

- Unique and open-source design
- Must be orderable on JLCPCB or other [approved vendor](./docs/VENDORS.md)
- Must be in high school[^1][^2] and show proof of high school enrollment to submit

[^1]: Home school still counts!
[^2]: If you left high school early you can also submit.

## Getting Started

### Star the repo (Optional)

To follow the repo for updates and show you're participating, click the "star" button on the [`onboard`](https://github.com/hackclub/OnBoard/) repo.

![Star the OnBoard repo](docs/images/directions/star-repo.png)

### 1. Join [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ) on Slack!

Our [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ) channel is where the party is getting started! If you haven't already joined, make sure to add yourself to the channel. And for those who are new to the Hack Club slack, sign up to our community of 13k+ makers through [here](https://hackclub.com/slack/?event=onboard) (don't worry, there isn't an application).

Perhaps ping a little hello to `@Kevin Yang`?

### 2. Design a Board!

It's design time! If you've done this before, you can skip ahead to step 3. Most people reading this will be new to PCB design, so we've made a simple tutorial on making an example board.

Watch [Maggie's NFC card tutorial](https://hack.af/business-card), where you'll make a design from scratch in a free online editor in under half and hour. This is jumping in the deep end- it won't explain everything, but it will give you a taste of what's possible. By the end you probably won't understand _what_ you did or _why_ you did it, but you will have a working design for a board and you'll know how to **tweak** and **edit** the design to make it your own.

_If you get stuck on this tutorial, or want more example projects to learn from, post in the Slack channel to hear from others going on their journeys._

### 3. Upload to a Vendor and Take a Screenshot

Upload your Gerber files to whatever vendor you prefer [^1] and add them to you cart. JLCPCB is the default PCB manufacturer, but you can shop around [^2]. Once completed, take a screenshot with cost included!
> If you're curious what all the settings are about or how to order for assembly, check out our [`ordering_from_JLCPCB.md`](./docs/ordering_from_JLCPCB.md) doc!

**Note:** Your screenshot is **VITAL** since your project cannot be approved without it. You'll include the screenshot in your PR later.

[^1]: Don't know which ones you can use? Check out [`VENDORS.md`](./VENDORS.md) for more info!
[^2]: If outside the US you may be charged customs which aren't covered by the grant! Check beforehand.

### 4. Fork!

Fork the [`onboard`](https://github.com/hackclub/OnBoard/) repo! This is the where you'll add your project files and eventually PR from!

![Fork the OnBoard repo](docs/images/directions/OnBoard-Fork.png)

### 5. Add Your Design to Your Project Repo

From your fork of `OnBoard`, create a folder with your project name under `OnBoard/projects`. To do this, go to the projects folder and click `Create new file`.

![Projects folder](/docs/images/directions/projects.png)

![Create new file](/docs/images/directions/add-file.png)

Then in the box labeled `name your file...`, type in `PROJECT_NAME/README.md`. This creates a README file under a folder called named after your project.

![Creating a folder](/docs/images/directions//creating-a-folder-highlighted.png)

After this, copy and paste the contents of [`TEMPLATE.md`](./projects/!Template/TEMPLATE.md?plain=1) into the text editor and fill it out!

![Paste in TEMPLATE.md](docs/images/directions/paste-in-template.png)

Once your done, press the big green `Commit changes` button to save!

With your README filled out, head over to add files to begin uploading your Gerber, design files, and screen shot of vendor approval.

![Upload gerber files](docs/images/directions/adding-gerbers.png)

In all, you should have the following files under your project folder:
- [ ] `README.md`: A filled out [`TEMPLATE.md`](./projects/!Template/TEMPLATE.md?plain=1), renamed to `README.md`
- [ ] `cart.png`: A screen shot of your vendor approving your board
- [ ] `Gerbers.zip`: This should be the file that you send off to the vendor.
- [ ] Design files (`design.json`, `design.sch`, `design.brd`, etc). Whatever format your designer outputs to should be included.

If you have all the above, you're done with this step!

### 6. Create a PR!

Once you've uploaded your files, you can merge them to the main repo through a pull request! Under the contribute tab of your forked repo, click the big green `Open pull request`.

![Open a PR](docs/images/directions/open-pr.png)

That will bring you to the main repo, where you'll initiate a pull request. Follow the checklist, we'll then review your PR and you'll be off to the races!

![Submission checklist](docs/images/directions/submission-checklist.png)

> Here's a quick preview of the [submission checklist](.github/PULL_REQUEST_TEMPLATE.md)
> ## Submission Checklist:
>
> - [ ] I am a current high school, middle school, or home schooled student.
>  - [ ] I have filled out the [verification form](https://airtable.com/shrbcDANe6ug6gj0p)
> - [ ] I have joined the [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ) channel on Slack
> - [ ] I made this board from scratch, even if I followed a tutorial
> - [ ] I have followed [DIRECTIONS.md](https://github.com/hackclub/OnBoard/directions.md)
>   - [ ] Created a folder under `onboard/projects`
>   - [ ] Filled out `TEMPLATE.md`
>   - [ ] Uploaded Gerber and design files
>   - [ ] Uploaded screen shot of PCB passing vendor inspection
>   - [ ] I am ordering the smallest batch size (ie. JLCPCB's smallest order is for 5 boards)
>   - [ ] If outside the US I've checked that I can afford the customs charges in my country (which isn't covered by the grant)


### 7. Ship it!

Post photos of your board in [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ)! We can't wait to see what you make!

![John sharing PCB](docs/images/directions/john-sharing-pcb.png)

## Example Projects

- [PCB Business Card with NFC](https://www.instructables.com/PCB-Business-Card-With-NFC/)
- [DIY Raspberry Pico Dev Board](https://01001000.xyz/2021-02-13-Raspberry-Pi-Pico-dev-board-Kiwikit/)
