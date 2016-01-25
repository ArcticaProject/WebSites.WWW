.. pub: 1
.. description: The Arctica Project's Community.
.. title: IRC Meeting HowTo


# Steps to run an IRC team meeting for the Arctica Project

## What is a team meeting?

Basically, whenever it comes to the situation that more than one or two
people start discussing issues relevant to the project's course, relevant
to some aspect of the development within the Arctica Project, we call
this a (sub)team meeting. If such meetings occur on IRC, we should make
sure they are documented for everyone else interested in the Arctica
Project.

Saying this, there are at least two types of meetings:

* Regular / scheduled meetings
* Spontaneous meetings that deserve a protocol

## Regular / Scheduled Team Meetings

### Step 1: Announcement Mail

Meeting announcements are either send anew or are included in the last
meetings summary mail. Let's presume we plan a new meeting from scratch.

* Preparations:

    * Find a date/time that works for as many people on the project. Please
    note, that we have various team members living in various time zones.
    Use ``#arctica`` on Freenode IRC or the [developers' mailing
    list](https://lists.arctica-project.org/listinfo/devs) for this.

    * Once a date/time for the meeting has been agreed upon , visit [Time
    and Date's timezone
    converter](http://www.timeanddate.com/worldclock/fixedform.html) and
    prepare an event query. The query is used in meeting invitation
    mails, so that people don't have to think about date/time
    conversions regarding different time zones that much.

    * Generate a shortened URL for that query's result at https://bitly.com/.

* Send an email announcement out to the [deverlopers' mailing
list](https://lists.arctica-project.org/listinfo/devs) with the following
template.

```
Subject: Announcement of Arctica Project IRC meeting, <dd>-<Month> @ <hh>:<mm> UTC

A new IRC meeting of Arctica Project members (and people otherwise
interested in our project) has been scheduled:

Date: <dd> <Month> <YYYY>
Time: <hh>:<mm> UTC, for your local time: <bitly.com-Short-URL>
Duration: <mm> minutes
Location: #arctica on Freenode IRC

Meeting Chair for this meeting will be <Real Name> (<IRC nick>).

Please propose discussion topics via the Arctica Project's developers'
mailing list:
https://lists.arctica-project.org/listinfo/devs

If you propose a topic, it is expected that you show up and present it,
or have a substitute participate in the meeting. It is important that
you're present at the meeting to guide the discussions in the direction
you want, so we do not spend time guessing what kind of info/answers you
may be looking for.

NOTE: Propose your topic by
<weekday-and-date-two-days-before-the-meeting>. Any topics added after
that will be considered for the following meeting. The next meeting's
chair will send out the meeting invitation / reminder with confirmed
agenda one day before the meeting.

Bye,
  <Real Name> (<IRC nick>)
```



### Step 1: Invitation / Reminder Mail

One day (~24h) before the meeting, the official meeting invitation
(acting as a reminder / update mail) containing the official meeting
agenda gets mailed by next meeting's chair via the [Arctica Project's
developers' mailing
list](https://lists.arctica-project.org/listinfo/devs).

```
Subject: Next Arctica Project IRC meeting, <dd>-<Month> @ <hh>:<mm> UTC

Here's the invitation/agenda for tomorrow's meeting:

Date: <dd> <Month> <YYYY>
Time: <hh>:<mm> UTC, for your local time: <bitly.com-Short-URL>
Duration: <mm> minutes
Chair: <Real Name> (<IRC nick>)
Location: #arctica on Freenode IRC

Those without an IRC client can access it here:
https://kiwiirc.com/client?settings=f0806f0b0080f3918e0a42eefdf2073d

Current proposed topics:

- Introduction (5 min)
- <topic-1>
- <topic-2>
- Wrap up and next meeting (5 min)

Please familiarize yourself with the topics before the meeting, as well
as the common MeetBot commands https://wiki.debian.org/MeetBot (it's used
for meeting management and logging)

Thanks and see you tomorrow!

Bye,
  <Chairman's full name>
```

### Step 2: Running the meeting

#### Meeting moderation

* Meeting Chair
    * The person who starts the meeting becomes the chair.
    * Those who become chair can guide the meeting.
    * Chairs can be added or removed with **#chair** *nick* and **#unchair** *nick*.
    * The chair(s) control the meeting's report via sending commands to the MeetBot.
*  Participants
    * Everyone else is a meeting participant
    * Participants can post during the complete course of the meeting.
    * Participants cannot use MeetBot commands.

#### As Participant

1. Join ``#arctica`` on ``irc.freenode.net``.

1. During the introduction phase introduce yourself by typing: **#info**
*Your Fullname*, *What-you-do-in-the-project*.

1. Whenever you feel like contributing, simply type something.

1. If you present any of the topics from the agenda, you may have
prepared some pre-written text that you want to copy-paste into the chat.
You can do this, but make sure to limit yourself when copy-pasting such
content.

#### As Meeting Chair

##### Start the Meeting and Set the Topic

1. Join ``#arctica`` on ``irc.freenode.net``.

1. Start the meeting with **#startmeeting** *Arctica Project IRC meeting,
<dd>-<Month> @ <hh>:<mm> UTC* at the agreed upon starting time of the
meeting. This will be the meeting name.

1. Set the channel's and meeting's topic via the first usage of the
command: **#topic** *Arctica Project IRC meeting, <dd>-<Month> @
<hh>:<mm> UTC*

1. Then loop over the meeting's agenda with **#topic** *agenda top-1*,
**#topic** *agenda top-2*, etc. Do this in the timely order of topics as
listed in the invitation mail's agenda. Normally the first item that
follows up is: **#topic** *Introduction (5min)*

Once the meeting has ended an email will be sent out to the meeting's
chair containing URLs# to the meeting's summary page and backlog. The
sent out mail template will be personalized and then forwarded to the
[Arctica Project's developer's mailing
list](https.//lists.arctica-rpoject.org/listinfo/devs/).


##### Assign Items to the Current Topic

The following commands should only be used by the meeting's chair.

* **#action** *somebody will read the entire Internet*
    * If the specified nick says something during the meeting it will get the action assigned.
    * The task is recognized to the nick even if it doesn't write anything with the **#some** *nick* command.
* **#info** *To summarize sum information presented throughout the discussion*
* **#idea** *Announce some idea*
* **#link** *here is some {url} with useful information about about xxx*
* **#help** *Look for somebody who knows about xxx*
* The last item can be removed with **#undo**.
* **#agreed** *To agree on something* (only chairs can agree on items)
    * Mark something as agreed.

##### End the Meeting

1. Don't forget to wrap up the meeting and agree on next meeting's time
and date. Normally you do enter this command for that five minutes before
the end of the meeting: **#topic** *Wrap-up and planning next meeting
(5min)*

1. End the meeting with **#endmeeting** when the meeting time is over.

### Wrap-up Mail and Announcement of Next Meeting

The meeting's summary mail is always sent to the meeting's chair. The
chair then is responsible for personalizing that mail and including
information on the next agreed upon meeting. Example:

```
Subject: [Minutes] Arctica Project community meeting <this-date> + planning for next one <next-date>

Thanks to everyone who attended today's meeting! We had a long but exciting
meeting filled with great discussions and positive news. If you missed it,
or if you want to relive it, here are the minutes/logs:

<copy-paste-automated-MeetBot-message-text-here>

The next meeting we have planned for <YYYY>-<MM>-<DD> @ <hh>:<mm> UTC.
Meeting Chair for that meeting will be <ReaL Fullname> (<IRC-nick>).

Please propose discussion topics via the Arctica Project's developers'
mailing list:
https://lists.arctica-project.org/listinfo/devs/

If you propose a topic, it is expected that you show up and present it,
or have a substitute participate in the meeting. It is important that
you're present at the meeting to guide the discussions in the direction
you want, so we do not spend time guessing what kind of info/answers you
may be looking for.

NOTE: Propose your topic by
<weekday-and-date-two-days-before-the-meeting>. Any topics added after
that will be considered for the following meeting. The next meeting's
chair will send out the meeting invitation / reminder with confirmed
agenda one day before the meeting.

Bye,
  <Real Name> (<IRC nick>)
```

## Spontaneous Meetings / Discussions

### Step 1: Agreement on starting the IRC MeetBot

While being in the middle of a discussion, people on IRC might realize
that the discussion is worth a MeetBot session. Immediately, you should
agree upon that what you are doing is actually a spontaneous meeting.

The person most experienced with the handling of the MeetBot shall
spontaneously become the meeting's chair and immediately
start the meeting via the MeetBot commands as described below.

### Step 2: Introduction

People attending shortly introduce themselves via: **#info** *<Real
Fullname>, <What you do in the project>*

### Step 3: Provide discussion backlog

The meeting's chair is responsible for providing a quick summary of the
discussions backlog before continuing the discussion. Make sure the
context of the current discussion becomes clear to third party readers.

### Step 4: Running the Meeting
For detailled instructions how to run the actual meeting, see above.

## History of meetings

You can find the history of all meetings at
http://arctica-project.org/meetbot/arctica/log/.
