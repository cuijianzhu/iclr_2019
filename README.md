# ICLR Reproducibility Challenge 2019

[Sign-up Form](https://docs.google.com/forms/d/e/1FAIpQLSehp6-IcArs4hzWB9gkPsR_abekpZrDXCGf27I5G4vZ5h1kFQ/viewform?usp=sf_link) | [Search ICLR for Papers](https://openreview.net/group?id=ICLR.cc/2019/Conference) 

Welcome to the 2nd edition of ICLR reproducibility challenge! One of the challenges in machine learning research is to ensure that published results are reliable and reproducible. In support of this, the goal of this challenge is to investigate reproducibility of empirical results submitted to the [2019 International Conference on Learning Representations](http://iclr.cc/).
We are choosing ICLR for this challenge because the timing is right for course-based participants (see below), and because papers submitted to the conference are automatically made available publicly on [Open Review](https://openreview.net/).

----

**News** : 

- **Journal Publication**: The results of ICLR Reproducibility Challenge 2019 is out in [Volume 5, Issue 2 of ReScience Journal](https://rescience.github.io/read/#volume-5-2019) 
- **Acceptance Decisions are out!**
- We have partnered with [ReScience](https://rescience.github.io/), where selected reproducibility efforts will be published as a special journal issue.
- **Deadline for submission: ~January 7th, 2019~ extended to January 12th, 2019**
----


## Accepted Reports

The following reports have been accepted for ICLR Reproducibility Challenge, and are published in [Volume 5, Issue 2 of ReScience Journal](https://rescience.github.io/read/#volume-5-2019).

PR: [146](https://github.com/reproducibility-challenge/iclr_2019/pull/146), [136](https://github.com/reproducibility-challenge/iclr_2019/pull/136), [150](https://github.com/reproducibility-challenge/iclr_2019/pull/150), [148](https://github.com/reproducibility-challenge/iclr_2019/pull/148)

Congratulations!

## Thanks to all Reviewers!

Many thanks to all our reviewers who spent their precious time to critically review the reports. We acknowledge your hard effort and hope that you will keep supporting us in this endeavour in the future! Many thanks to (in alphabetical order):

- Andrew Jaegle, University of Pennsylvania
- Arna Ghosh, McGill University
- Chaochao Lu, University of Cambridge
- Ishan Durugkar, University of Texas at Austin
- Jiahui Yu, University of Illinois, Urbana Champaign
- Joelle Pineau, Facebook AI Research / McGill University
- Joey Bose, Mila / McGill University
- Lovedeep Gondara, Simon Fraser University
- Maneesh K Singh, Verisk
- Martin Jaggi, École polytechnique fédérale de Lausanne
- Malik Altakrori, Mila / McGill University
- Melanie Fernandez Pradier, Harvard University
- Michela Paganini, Facebook AI Research
- Mido Assran, Facebook AI Research / McGill University
- Nicolas Gontier, Mila / Element AI
- Noe Casas, Universitat Politecnica de Catalunya
- Olexa Bilaniuk, Mila / Université de Montréal
- Pablo Samuel Castro, Google Brain
- Peter Henderson, Stanford University
- Rosemary Nan Ke, Mila / Facebook AI Research
- Ryan Lowe, Mila / Facebook AI Research
- Shagun Sodhani, Mila / Université de Montréal
- Seungjae Ryan Lee, END-TO-END AI, Princeton University
- Xavier Giro, Universitat Politecnica de Catalunya


----

## Task Description

You should select a paper from the 2019 ICLR submissions, and aim to replicate the experiments described in the paper. The goal is to assess if the experiments are reproducible, and to determine if the conclusions of the paper are supported by your findings. Your results can be either positive (i.e. confirm reproducibility), or negative (i.e. explain what you were unable to reproduce, and potentially explain why).

**Essentially, think of your role as an inspector verifying the validity of the experimental results and conclusions of the paper. In some instances, your role will also extend to helping the authors improve the quality of their work and paper.**

You do not need to reproduce all experiments in your selected paper, for example the authors may experiment with a new method that requires more GPUs than you have access to, but also present results for a baseline method (e.g. simple logistic regression), in which case you could elect to reproduce only the baseline results. It is sometimes the case that baseline methods are not properly implemented, or hyper-parameter search is not done with the same degree of attention.

If available, the authors' code can and should be used; authors of ICLR submissions are encouraged to release their code to facilitate this challenge. The methods described can also be implemented/re-implemented according to the description in the paper. This is a higher bar for reproducibility, but may be helpful in detecting anomalies in the code, or shedding light on aspects of the implementation that affect results.

## Registration & Workflow

### Select a paper and avoid duplicate work

We will be using this repository primarily to organize the challenge. Once the ICLR paper review period starts, [our form](https://docs.google.com/forms/d/e/1FAIpQLSehp6-IcArs4hzWB9gkPsR_abekpZrDXCGf27I5G4vZ5h1kFQ/viewform?usp=sf_link) will be live for participants to _claim_ a paper. Unlike last year's challenge, this year we want to encourage participants to avoid duplicate reproducibility efforts. Thus, before registering for the challenge [go through our open issues](https://github.com/reproducibility-challenge/iclr_2019/issues) to search for the papers which are already claimed by other participants. You can search by the paper name or by the OpenReview ID, which you will need to submit at the time of registration. You can also claim a paper which has been "relinquished" (more on that below).

### Submit form and note issue number

Now we are ready to submit the form. Fill the required questions, and make sure you have the following details handy:

- OpenReview paper ID
- Github login ID of the team lead

Once you submit the form, a Github issue will be created for your claim. Take note of this issue number (#xxxx). Participant details are kept anonymous from the issue, only the Team Name and Institution name should be visible for the claim. You are encouraged to contact the authors in private to clarify doubts regarding the paper but you should maintain your anonymity in the issue section before your report submission.

### Post reproducibility project

After your reproducibility project is complete, you should:

- Change the label of your issue from "in-progress" to "complete". Note this is when you make yourself public. To do that, mention the organization owner [@reproducibility-org](https://github.com/reproducibility-org) and comment the following: `@reproducibility-org complete`. Since in the form we asked your team lead's Github ID, this command can only used by him/her. We verify your ID and if you are assigned to this particular issue then we change the label of the issue to "complete".
- Post a public description of your report as a comment to the linked OpenReview forum. This report should be brief (300-400 words) detailing the key findings of your report.

#### Submission Instructions

- Submit a PR referring to the issue where you submit your report.
  - Your report should be in [ICLR Latex template](https://www.overleaf.com/latex/templates/template-for-iclr-2019-conference-submissions/cgrnhwjpnfsv).
  - Your report should be within 5-8 pages.
  - To submit the report, open a [Pull Request (PR)](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) to our Github repository:
  - Fork our repository to your Github account
  - Create a folder with your team name & paper ID within “papers” folder. For example, if your team name is “ABC” and paper ID is “abcXYZ123”, then the folder name should be “ABC-abcXYZ123”.
  - Upload your report in the folder (compiled pdf only)
  - Include a README file in the folder which has a link to your codebase and link to your issue
  - Open a Pull Request (PR) to our repository
  - In the description of the Pull Request, mention your issue number (#x)
  - Your report should also contain a link to your reproducibility codebase.


### Leaving the competition

If you choose to leave the competition, please comment the following: `@reproducibility-org close` which will close the issue if you are the valid owner of the issue. If you want to work on another paper or work on the same paper, you will have to resubmit our form.

## Participating Institutions

- [COMP 551, Applied Machine Learning](http://sarathchandar.in/teaching/2018/fall/comp551/), McGill University
- [COMP 652, Machine Learning](https://rllabmcgill.github.io/COMP-652/index.html), McGill University
- [11-785 Introduction to Deep Learning](http://deeplearning.cs.cmu.edu/), Carnegie Melon University
- [CS 4803 / 7643 Deep Learning](https://www.cc.gatech.edu/classes/AY2019/cs7643_fall/), Georgia Tech
- [Neural Networks and Deep Learning](https://sites.google.com/a/cs.uni.wroc.pl/jch/teaching/fall2018-2019/neural-networks-fall-18), University of Wroclaw
- [STAT 946, Deep Learning](https://uwaterloo.ca/data-analytics/teaching/deep-learning-2017), University of Waterloo
- [STAT 441/841/CM763 : Classification](https://uwaterloo.ca/data-analytics/statistical-learning-classification), University of Waterloo
- [GIF-4101 / GIF-7005 : Introduction à l'apprentissage machine](http://vision.gel.ulaval.ca/~cgagne/enseignement/apprentissage/A2018/), Université Laval
- [CS 433 : Machine Learning](https://mlo.epfl.ch/page-157255-en-html/), EPFL
- [TELECOMBCN 230706 Deep Learning for Artificial Intelligence](https://telecombcn-dl.github.io/2018-dlai/), Universitat Politecnica de Catalunya

Instructors teaching a graduate-level machine learning course in Fall 2018 are encouraged to use this challenge as their final course project. The project can be completed individually or in small groups. Participation by other researchers or research trainees with adequate machine learning experience is also encouraged. Contact [Joelle Pineau](mailto:jpineau@cs.mcgill.ca) or [us](mailto:reproducibility.challenge@gmail.com) to register your course.

## Available resources

- Instructors can apply for [Google Cloud credits](https://cloud.google.com/edu/) for their students. Each student will be given a small number of credits to start (approx. $50).
- By default, Google Cloud accounts don't come with a GPU quota, but you can find instructions on how to request GPUs, including links on how to check and increase quotas, [at this link](https://cloud.google.com/compute/docs/gpus/add-gpus).
- If necessary, instructors can ask for much more computing credits (up to $1000 per student) by contacting: [CloudEDUGrants@google.com](CloudEDUGrants@google.com).
- Students can also request a $300 credit.
- If you are another company that can offer cloud computing credits, please contact [reproducibility.challenge@gmail.com](mailto:reproducibility.challenge@gmail.com). 

## Proposed outcomes

Participants should produce a Reproducibility report, describing the target questions, experimental methodology, implementation details, analysis and discussion of findings, conclusions on reproducibility of the paper. This report should be posted as a contributed review on OpenReview.

The result of the reproducibility study should NOT be a simple Pass / Fail outcome. The goal should be to identify which parts of the contribution can be reproduced, and at what cost in terms of resources (computation, time, people, development effort, communication with the authors).

Participants should expect to engage in dialogue with ICLR authors through the OpenReview site. In cases where participants have made significant contributions to the final paper, ICLR should allow adding these participants as co-authors (at the request of the original authors only.) 

## Important dates

- Announcement of the challenge: Early September 2018
- Registration of participants: Anytime during the fall
- Final submission of reproducibility report: **~January 7th, 2019~ January 12th, 2019**


## Suggested Reading List

[See this list](https://www.cs.mcgill.ca/~jpineau/ICLR2018-ReproducibilityChallenge-Readings.pdf). 

## Questions?

Drop us a mail at [reproducibility.challenge@gmail.com](mailto:reproducibility.challenge@gmail.com)

## Contact & People

- [Genevieve Fried](mailto:genevieve.fried@mail.mcgill.ca), logistics and registration
- [Rosemary Nan Ke](mailto:rosemary.nan.ke@gmail.com), references, advertising and technical support
- [Hugo Larochelle](mailto:hugolarochelle@google.com), corporate sponsorship
- [Koustuv Sinha](mailto:koustuv.sinha@mail.mcgill.ca), academic liaison
- [Joelle Pineau](mailto:jpineau@cs.mcgill.ca), challenge coordinator

