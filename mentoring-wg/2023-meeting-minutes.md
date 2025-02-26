---
title: TAGCS Mentoring Working Group Monthly Meeting (2023)
tags: Meeting Minutes, 2023
---

[![hackmd-github-sync-badge](https://hackmd.io/7vA7fKNrRG6KrGbA01oupw/badge)](https://hackmd.io/7vA7fKNrRG6KrGbA01oupw)


CNCF TAG Contributor Strategy
# Mentoring Working Group


## About TAGCS Mentorship Working Group

* [Primary repository](https://github.com/cncf/mentoring)
* CNCF Slack: [#tag-contributor-strategy](https://cloud-native.slack.com/archives/CT6CWS1JN)
* [Discussion boards](https://github.com/cncf/mentoring/discussions)
* [Email list](https://lists.cncf.io/g/tag-cs-mentoring-wg/)


## Meeting details

### Recurring monthly
* 2nd Tuesday of the month at 9PM UTC
* 4th Tuesday of the month at 9PM UTC (during the setup phase)

[CNCF Public Events - TAG CS Mentoring WG](https://tockify.com/cncf.public.events/monthly?search=CNCF%20TAG%20Contributor%20Strategy%20Mentoring%20WG)

### Zoom

Zoom Meeting  
https://zoom.us/my/cncftagcontributorstrategy?pwd=TnI0WU9Eb2I1RlRWdkl1R0k1WkZXUT09

Passcode: 77777


## April 11, 2023

21:00 UTC (2:00 PM PDT on 2023-01-11; 10:00 AM NZST on 2023-01-12)  
**Note**: this meeting may be cancelled or postponed due to its proximity to KubeCon EU.

### Attendance

* Riaan Kleinhans
* Josh Berkus
* Nate W. (briefly) 

More of a conversation than a meeting, should not be posted to Youtube.

### Updates/reminders

* Nate W. availability updates:
  * travelling for KubeCon EU April 13-21, 2023
  * vacation April 24-28, 2023 (Note, Nate can be available during this time as there is a GSoC deadline this week)
      * Move out to 5 May 2023

### Agenda

* LFX Term 02-Jun-Aug
    * We should draft an email to open the next term of LFX: https://github.com/cncf/mentoring/tree/main/lfx-mentorship/2023/02-Jun-Aug
        * issue: https://github.com/cncf/mentoring/issues/926
        * Should note that any GSoC projects that aren't accepted would be a great project for LFX term 02
        * previous email: https://lists.cncf.io/g/tag-cs-mentoring-wg/message/7
            * should send to: tag-cs-mentoring, toc list, add to Maintainer newsletter, cncf/mentoring discussions board, #mentoring slack
    * Should we push the deadline for project ideas back a week? - Move out to 5 May 2023
    * Should we create a templates folder in the cncf/mentoring repo for common communications like this?
        * Yes, that make sense
        * Make sure we do not forget any info
        * Let's make templates and review as a group
* LFX Term 01-Mar-May
    * Currently going through evaluations, evals due Wednesday Apr 12 @ 5:00pm pacific time
* GSoC
    * Currenly assessing contriubtor proposals
    * details & dates: https://github.com/cncf/mentoring/discussions/918#discussioncomment-5548149 
* Mentoring repo refactor:
    * https://github.com/cncf/mentoring/pull/927 - update to call out draft pages
    * https://github.com/cncf/mentoring/pull/899
    * Happy day!! It is merged!!


# Past Meetings

## March 28, 2023

21:00 UTC (2:00 PM PDT on 2023-01-28; 10:00 AM NZST on 2023-01-29)

### Attendance

* Nate W.
* Jay Tihema
* Ali Ok
* Riaan Kleinhans

### Updates/reminders

* 

### Agenda

* Nate W. goofed a sync merge, and accidentally merged it into `main` rather than `v2`
    * Mistake was reverted
    * Some history seems to have been lost
    * Need to recrate the v2 PR as the original one was closed in the mistake
    * Some issues tied to PR 773 have been closed as part of the "fixes:" automation
    * **Lessons learned:**
        1. Don't do complex (or even simple) merges on important projects when you're tired or otherwise disctracted
        2. Don't bypass security measures put in place to protect the `main` branch -- especally when doing 1. above
        3. The revert function works suprisingly well, but seems to have stripped out some of the history. Revert doesn't undo closed issues or PRs.
        4. Don't be afraid of making changes or mistakes because there's very little that can't be undone (though, don't be afraid to ask for help if you get git in over your head)
* **Walk through of cncf/mentoring v2 repo update**
  - https://github.com/cncf/mentoring/pull/733 - closed accidentally. Nate to open new one.
  - **New tracking PR**: https://github.com/cncf/mentoring/pull/899
  - Riaan & Jay
* **KubeCon**
    * TAG Contributor Strategy: What We Get Out of It (and You Could Too!)  
      Date and time: Thursday April 20, 2023 15:25 - 16:00 CEST  
      Room: Auditorium Center | G109  
      https://sched.co/1HzdC
    * Mentorship Office Hours
      Date and Time:  Wed, 19 April, 14:30 - 16:30  
      Room: E101  
      Seating: Boardroom 16pax  
      https://sched.co/1KWw8
    * Tech Docs Office Hours (if you're interested 🙂)  
      Date and Time:  Thur, 20 April, 11:00 - 12:30  
      Room: E101  
      Seating: Boardroom 16pax  
      https://sched.co/1KWw2
* **When is the good time to merge v2?**

### Notes
**V2 merge accident**
* Set of GitHub actions hacks that can provide some functions of PROW - Rob Kielty has done some work on these and might offer some solutions to avoid recurring/similar issues
* Can be helpful to let people know these kind of mistakes are ok and can happen - and important they know they can seek help/support when needed to navigate the space

**Walk through of cncf/mentoring v2 repo update**
* Updated V2 repo, initial changes made, Riaan/Nate made additional updates in mentee/mentor section. 
* New PR #899 - (initial changes shown)
* Main branch currently shows multiple scattered files and info. V2 is a rearrangement of pre-existing information to be more accessible for various user types
* Have created new content sitting under Mentee or Mentor-specific ReadMes with a more logical flow and consistent layout across both sections
* Will need to be set up so things are obvious and organised in their flow moving forward; also factoring other points such as *'How to be a mentor in GSOC'* etc.
* Project Board - mentoring issues, public calendar and CoC to be addressed
* *Will need to double-check Nate's PR cleanup to ensure things are set out as needed*
* May be some broken links from outside, but can be detected internally e.g. Google Analytics(?) or other automated systems, but possibly not high-priority at this stage
* Working on this Repo can likely be a recommended 'Good First Issue' for new Contributors
* Shouldn't need TOC approval with it not being website content, but TAG review would be appreciated with lots of changes having been made
* Can possibly look at integrating mentee/mentor/program info into Contributor.io eventually
* *Josh will review w/ Carolyn before approval*

**KubeCon**
* *TAG Contributor Strategy: What We Get Out of It (and You Could Too!)* - panel discussion 
* *Mentorship Office Hours* - room booked for a couple of hours to chat w/ maintainers on how to write proposals; first come, first served
    * More in attendance, the better (Weds 2.30pm-4.30pm)
* *Tech Docs Office Hours*

Join us at times listed!

**When is the good time to merge v2?**
* Would like to merge sooner than later; mindful of upcoming Kubecon. GSOC deadlines few weeks away so timing is good
* Would be ideal to have set up before KC EU


## March 14, 2023

21:00 UTC (2:00 PM PDT on 2023-03-14; 10:00 AM NZST on 2023-03-15)

### Attendance
* Nate W.
* Riaan Kleinhans
* Hippie Hacker
* Justin Vice
* Alexandre Nicastro
* Josh Berkus

### Agenda

* All comments have been addessed in [start contributing to open source
#339](https://github.com/cncf/tag-contributor-strategy/pull/339)
    - Should we merge it?
    - Clotributor question
    - Nate to put Riaan in touch with CNCF blog team
    - NATE: YouTube Series : Getting Started
      - process, downloading, finding issues
      - how to contribute to Open Source
      - Maybe Ambassador?
* GSoD PRs in today -- could use some help reviewing
    - https://github.com/cncf/mentoring/pull/877
    - https://github.com/cncf/mentoring/pull/875 
    - Org applicaitons due March 24, 2023 at 18:00 UTC
* GSoC
    - Admin guide PR: https://github.com/cncf/mentoring/pull/871
    - March 20th, mentors can start giving feedback at that time
    - Mentors are already in the system
* simple coder templates
  - https://github.com/cncf-infra/coder-templates/tree/main/simple
  - https://github.com/cncf-infra/coder-templates/tree/main/simple-packet
  - https://github.com/ii/emacs-coder/blob/master/templates/emacs-pod/main.tf
* Tauranga Kids Day March 31st
  - https://github.com/orgs/workshop-coop/projects/3
* KubeCon EU Kids Day April 15th
  - https://github.com/orgs/workshop-coop/projects/1
  - workshop.coop hosted coder instance with templates for littil.org KubeCon Kids Day.
  - https://hackmd.io/rHr0DSGpRnmlGzI1p-WzWw
* KubeCon mentoring office hours 
  - 2 hours, time date tbd
  - free form discussion, have a question about CNCF Mentoring, come by and say hi 
* V2 review
  - https://github.com/cncf/mentoring/pull/733

## February 28, 2023

21:00 UTC (1:00 PM PST on 2023-02-28; 10:00 AM NZST on 2023-03-01)

### Attendance

* Nate W.
* Jay Tihema
* Ali Ok
* Riaan Kleinhans
* Josh Berkus
* Alexandre Nicastro
* Parashar Singh

### Agenda

* Adding Ali Ok to GSoC CNCF administration team
* LFX Mentorship Term 1 updates
  * Nate W. would like to accept applicants as mentors make selections, rather than as a batch on Friday/Monday. (This also gives us more opportunity to adjust when mentors make the same selection)
* Project Board/Management  
  https://github.com/orgs/cncf/projects/16/views/1

### Notes

* Ali Ok accepted as GSOC admin, new process in ongoing review, operations/comms will be conducted in open and continue refinement going forward. 
* LFX Term 1 updates - 20% all mentors have made their selections; may have missed deadline notification prior > 7 March. 
    * Suggested acceptance process starts now to reduce admin processes w/ Nate and LFX. Nate will send an email and post to confirm
* Contacts to go to Natali from previous meeting
* Question about GSoD: https://github.com/cncf/mentoring/discussions/843#discussioncomment-5052374
    * Not yet run as an org (Nate); GSOD issue last year - allowed only one project per year previously. **Reach out to Google and clarify/confirm any project submission limitations.**
    * (Previously one project per OS project)
    * > (b) Each Organization may submit one (1) Organization Application. https://developers.google.com/season-of-docs/terms/program-rules
    * Timeline: https://developers.google.com/season-of-docs/docs/timeline
* Alexandre experiencing multiple enquiries regarding getting started in Mentoring
    * (Josh) need clarity about target audiences; persona-based responses 
    * Queries generally broad and inconsistent - general 'guidance'-based questions
    * Resources/guides would need to linked to support navigation; conscious of large workload to inform/build fundamental understanding
    * Potential contributors might be cautious of needing 'permission' of getting involved to begin with
    * This would go at: https://contribute.cncf.io/contributors/
    * Maybe a short video can be recorded (can be asked from CNCF Ambassadors)(example) https://www.youtube.com/watch?v=msyGybzCKRs
    * Potential personas
      * new to open source
      * new to cloud native
      * folks changing careers(?)
        * may not lead to sustained contributions (NW + JB)
        * may be an in to opensource regardless (JT + AN)
        * Ongoing discussion needed; to refer to TAG-CS
        * File an issue, attach to draft doc in HackMD/Google Docs, mention on Slack - pertains to both mentoring and Contributor Growth
      * folks assigned by their company to work on open source
      * AN to open issue: https://github.com/cncf/tag-contributor-strategy/
        * Previous Slack discussion https://cloud-native.slack.com/archives/CT6CWS1JN/p1675715555437939
* 65 projects proposed for LFX, not all proposals have viable candidates at this stage
* GSOC - March 20 potential contributors to propose, expecting comms in boards re upstream issues 

## February 14, 2023

21:00 UTC (1:00 PM PST on 2023-02-14; 10:00 AM NZST on 2023-02-15)

### Attendance
* Nate W 
* Jay Tihema
* Ali Ok
* Alexandre Nicastro
* Natali Vlatko
* Riaan Kleinhans

### Agenda
* Google Season of Docs -- Org applications start tomorrow
  * Next steps?
  * Historically we only get 1-2 slots
* Notification template - informing Mentees of preferred processes > TAG-CS template
  * https://cloud-native.slack.com/archives/CT6CWS1JN/p1675715555437939
* Timeline proposals for LFX Mentorship Terms 2 & 3: https://github.com/cncf/mentoring/pull/833
* LFX promotion on available channels
    * Social boosts for LFX Mentorship Term 1 applciations
      * https://twitter.com/CloudNativeFdn/status/1625192237587111936
      * https://mstdn.ca/@natew/109864484786454672
      * https://www.linkedin.com/feed/update/urn:li:activity:7031335091217809408 
* v2 additions, workload > PRs

### Notes

**GSOD** 
* Applications starting tomorrow. Would like to apply as an org; requires doc project proposals to support application submission.
* Not expected to have as many slots available this year, but would like to proceed regardless. Nate will create PR to set up GSOD.

**Notification template for Mentees**
* Following thread in TAG-CS Slack - response to lots of 'noise' in #mentoring w/ general questions vs. support of upstream issues.
* Msg replies not necessarily helpful in redirecting or addressing issue. Need to create more effective responses e.g. *template as well as support/training to also foster positive engagement and retention.*
* Need multiple fronts to 'teach' the preferred behaviour; in addition to Ambassadors supporting this, having coordinated responses
* Matter of coaching people out of learned behaviours that might not be constructive to attaining opportunities or impacting future relationships; may be less about *contributing* than not even investigating the project to begin with.
* Better to have template 'available', or respond to every such request/query each time - how to best manage overall 'noise'? e.g. responding to multiple instances than every single one.
* https://hackmd.io/W-VB1zZtTnOJFBSWR3frUA (working doc)

**Timeline proposals for LFX mentorships Term 2-3**
* Open for discussion

Social links boost, need support/please share!
* Deadline is 21/2/23

**V2**
* Current layout/format ineffective in guiding mentees/mentors effectively, as well as structuring/archiving program information. 
* User perspective vs. group view on what's needed in this Repo - to help group determine what needs to be updated first e.g. who will be engaging with this resource.
* Can utilise mentees/mentors to review and provide feedback - previous mentees for could be more beneficial (even limited numbers)
  * TODO: Nate to reach out to find folks, Natali to run interviews
* Could potentially request mentees at program completion review the Repo as well. 
* Need to confirm what is needed to produce an MVP ahead of potential merge in the next month
* Contributions - comment PR-level discussions; link any new PRs against V2 to maintain visibility.
* Umbrella PR: https://github.com/cncf/mentoring/pull/733

**CLOTributor**
* Being positioned as preferred 'job boards' to promote opportunities for contributors; recommended to focus here for development.

## January 24, 2023

21:00 UTC (1:00 PM PST on 2023-01-24; 10:00 AM NZST on 2023-01-25)

### Attendance

* Nate W.
* Ali Ok
* Josh 
* Alexandre
* Riaan
* Jay

### Agenda

* LFX Mentorship Project Proposals
  * https://github.com/cncf/mentoring/tree/main/lfx-mentorship/2023/01-Mar-May
* 2023 Goals
  * https://hackmd.io/@tag-cs-mentoring-wg/2023-goals
* Repo revisions
  * project board: https://github.com/orgs/cncf/projects/16/views/1
* GSoC Org applications
  * Nate W. to work with Chris A. to apply as an org
  * https://groups.google.com/d/msgid/google-summer-of-code-discuss/649212c4-fe0d-4cb6-8e48-17f961e3d0ben%40googlegroups.com?utm_medium=email&utm_source=footer

- Ali:
Could we have the [Ideas page](https://github.com/cncf/mentoring/blob/main/summerofcode/2022.md) open earlier? Motivation for the ask is that the potential mentees want to start exploring the project ideas earlier. Similarly, maintainers want to list their ideas earlier for encouraging a head start.

- Options are making the Ideas page availible through out the year
- Incorporate CLOtributor with the process with `Help wanted` & `Mentor Available` labels
    - AI: Riaan & Jay add CLOTributor to the Mentoring repo
- **Could use Git discussions for this as well.** 
    - GSOC 2022 - Nate opened a thread to support this, however only 15% of this thread was used; also creating alot of overhead to maintain. Because this will all link back to upstream issues; preferred this would occur off the boards. 
    - Might also be hard to filter convos back into the issues themselves as well. An ideas page however would give a centralised reference point for those seeking information. 
    - We should keep encouraging mentees to reach out to potential mentors; aiming to give mentors more time to make their selections as well.
    - Having alot of mentees/applicants can be difficult to filter/process effectively otherwise.
    - Another option might be for mentees to 'source' their own mentors to support/drive projects as well > Application Process
        - If a potential mentee is interested in a CNCF project and wants to do a mentorship, this should put the impetus on the mentee themselves; this mechanism currently exists but is not explicitly communicated.
        - This might be an issue especially for paid mentorships such as LFX. This could be exploited from a faculty of an education provider for instance that could implement their own mentee without following the preferred process.  
**How to incorporate Clotributor into the existing onboarding process?** Future working session(s) to determine best course of action.

**Repo update**
- Thank you for review Ali & Nate
- Next step might be to merge in v2 branch
    - Then clean up and distill information in Mentee and Mentor files to a single readme for people to the contribute
    - Try and make the info clear one stop place to find info
    - Might have to hold back on merging in the v2 branch because links have been publish to current repo info.
    - When would be a good time to remove the WIP label from the PR.
        - Likely after updating Mentee and Mentor sections is in a workable state + FAQs
* Should be rebasing but leave number of commits
* Folder restructure, mentee/mentor page and FAQ
* GitHub doesnt have a redirection tool; maintainters have been notified, potential applicants will seek this information - work can be continued once ideas have been confirmed/agreed upon, possibly next week.
Q. Keep v1 page blank with link to v2 page
Edit page we would link to, highlight page move. Can hold off on this until the last minute; let's keep it clean in the meantime. 

Links important to share with others - Mentoring tree main, LFX Mentorship 2022... [link](https://github.com/cncf/mentoring/tree/main/lfx-mentorship/2023/01-Mar-May)

## January 10, 2023

21:00 UTC (1:00 PM PST on 2023-01-10; 10:00 AM NZST on 2023-01-11)

### Attendance

* Nate W.
* Riaan K.
* Asare N.
* Josh Berkus
* Alexandre N.

### Updates/reminders

* [2022 Meeting Minutes](https://hackmd.io/@tag-cs-mentoring-wg/monthly-meeting) file has been set to read only for most users and [is being archived](https://github.com/cncf/mentoring/pull/756).

### Agenda

* Mentoring WG Calendar https://calendar.google.com/calendar/u/0?cid=Y18wNTMzNWEwNDhjYjMyNTk3NTRmZjAzYzgwM2MyN2FjMDhmMjFkZTc4OTYyMDhkMmI1NWFjMmM1MTIzNDlhZDFiQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20
* LFX Mentorship Project proposals open Jan 16
  * https://github.com/cncf/mentoring/tree/main/lfx-mentorship/2023/01-Mar-May
  * email toc mailing list
* Repo revisions - to create a work session to discuss/rework.
* [Nate W.] Do we still need the temp 2nd monthly meeting? (We should defer this question to a meeting that Jay can attend)
* KubeCon Amsterdam
    * workshop re: how to be a good mentor (proposal writing, selecitng mentees, etc.)
    * Speed mentoring co-operation
      * find out who to chat with about this
* 2023 Mentorship goals
  * Increase diversiy of participants
      * How do we increase awareness in  geographical diverse places?
      * Students in academic communities in new locations
          * LM
          * Africa
  * 150 mentees participating across all programs
  * work with LF research team to better understand trends
  * work with LF training to create a training course for mentors
  * work with LF mentoring admins to reach out to universities to work with co-op programs
  * increase number of programs we participate in
      * ex. Outreachy
      * recruit community members to help manage/run the programs
  * others?
    * [name=Nate W.][time=Thu, Jan 12, 2023 10:05 AM] Look into creating a 2-term program for longer/larger projects (How would this work with the req that mentees can only participate in one mentorship)
    * [name=Nate W.][time=Thu, Jan 12, 2023 1:13 PM] Reduce percentage of failed/withdrawn mentees
    
* Organize projects (and SIGs and TAGs) to supply an ongoing list of mentorship opportunities based on the Clotributor.
    * https://clotributor.dev/
    * That way we can reach out based on existing tasks
    * Plus skim a list of potential mentors
* Participate in MC, doing session on "participating in mentorship programs"
    * Nate + 1-2 project maintainers who did mentorships


---

# Meeting Template

## March 14, 2023

21:00 UTC (2:00 PM PDT on 2023-01-10; 10:00 AM NZST on 2023-01-11)

### Attendance

* 

### Updates/reminders

* 

### Agenda

* 

### Notes

* 

---

# Archives

* [2022 Meeting Minutes](https://github.com/cncf/mentoring/blob/main/TAGCS-Mentoring-WG/2022-meeting-minutes.md)
* [June 30, July 12, July 26, 2022](https://docs.google.com/document/d/1ZVFf_GRB5yrcTQieudtk3W-gWL6KuwHn1QG8XKdrARo/edit?usp=sharing)