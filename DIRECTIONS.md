# Directions
Interested in submitting to OnBoard? You're in the right place!

## 1. Join [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ) on Slack!
Our [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ) channel is where the party is getting started! If you haven't already joined, make sure to add yourself to the channel. And for those who are new to the Hack Club slack, sign up to our community of 13k+ makers through [here](https://hackclub.com/slack/) (don't worry, there isn't an application).

Perhaps ping a little hello to `@Kevin Yang`?

## 2. Fork!
Fork the [`onboard`](https://github.com/hackclub/OnBoard/) repo! This is the where you'll add your project files and eventually PR from!

![Fork the OnBoard repo](docs/images/directions/OnBoard-Fork.png)

## 3. Design a Board!
It's design time! Head over to an eCAD software of your choice ([EasyEDA](https://easyeda.com/), [KiCAD](https://www.kicad.org/), [Eagle](http://eagle.autodesk.com/)) and start designing!

Never designed before? No problem! We have design resources for [EasyEDA](https://easyeda.com/), a free online eCAD program. We'll be adding tutorials to [`design_resources.md`](./docs/design_resources.md) as we record them!

## 4. Upload to JLCPCB and Take a Screenshot
Upload your Gerber files to JLCPCB and add them to you cart. Once completed, take a screenshot with cost included!
> If you're curious what all the settings are about or how to order for assembly, check out our [`ordering_from_JLCPCB.md`](./docs/ordering_from_JLCPCB.md) doc!

**Note:** Your screenshot is **VITAL** since your project cannot be approved without it. You'll include the screenshot in your PR later.

## 5. Add Your Design to Your Project Repo
From your fork of `OnBoard`, create a folder with your project name under `OnBoard/projects`. To do this, go to the projects folder and click `Create new file`.

![Projects folder](/docs/images/directions/projects.png)

![Create new file](/docs/images/directions/add-file.png)

Then in the box labeled `name your file...`, type in `PROJECT_NAME/README.md`. This creates a README file under a folder called named after your project.

![Creating a folder](/docs/images/directions//creating-a-folder-highlighted.png)

After this, copy and paste the contents of [`TEMPLATE.md`](https://github.com/cjdenio/OnBoard/blob/main/projects/!Template/TEMPLATE.md?plain=1) into the text editor and fill it out!

![Paste in TEMPLATE.md](docs/images/directions/paste-in-template.png)

Once your done, press the big green `Commit changes` button to save!

With your README filled out, head over to add files to begin uploading your Gerber, design files, and screen shot of JLCPCB approval.

![Upload gerber files](docs/images/directions/adding-gerbers.png)

In all, you should have the following files under your project folder:
- [ ] `README.md`: A filled out [`TEMPLATE.md`](./TEMPLATE.md), renamed to `README.md`
- [ ] `JLCPCB.png`: A screen shot of JLCPCB approving your board
- [ ] `Gerbers.zip`: This should be the file that you send off to JLCPCB.
- [ ] Design files (`design.json`, `design.sch`, `design.brd`, etc). Whatever format your designer outputs to should be included.

If you have all the above, you're done with this step!

## 6. Create a PR!
Once you've uploaded your files, you can merge them to the main repo through a pull request! Under the contribute tab of your forked repo, click the big green `Open pull request`.

![Open a PR](docs/images/directions/open-pr.png)

That will bring you to the main repo, where you'll initiate a pull request. Follow the checklist, we'll then review your PR and you'll be off to the races!

![Submission checklist](docs/images/directions/submission-checklist.png)

> Here's a quick preview of the [submission checklist](.github/PULL_REQUEST_TEMPLATE.md)
> ## Submission Checklist:
> - [ ] I am a current high school, middle school, or home schooled student.
> - [ ] I have followed [DIRECTIONS.md](https://github.com/hackclub/OnBoard/directions.md)
>   - [ ] Created a folder under `onboard/projects`
>   - [ ] Filled out `TEMPLATE.md`
>   - [ ] Uploaded Gerber and design files
>  - [ ] Uploaded screen shot of PCB passing JLCPCB inspection

## 7. Ship it!
Post photos of your board in [`#onboard`](https://hackclub.slack.com/archives/C056AMWSFKJ)! We can't wait to see what you make!

![John sharing PCB](docs/images/directions/john-sharing-pcb.png)
