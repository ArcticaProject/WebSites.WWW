.. pub: 1
.. description: The Arctica Project's Community.
.. title: IRC Meeting HowTo

# Steps to run an IRC team meeting for the Arctica Project
* * *

## What is a team meeting?

Basically, whenever it comes to the situation that more than one or two
people start discussing issues relevant to the projects course, relevant
to some aspect of the development within the Arctica Project.

There are two types of meetings:

- Regular / scheduled meetings
- Spontaneous meetings that deserve a protocol

## Spontaneous meetings

## Regular / Scheduled Team Meetings

### Step1: Announcement

- Send an email announcement out to the list with the following template and agree with the members when to run it.

```
Subject: Some subject goes here, 21:00 UTC

Some description and comments goes here

- Some item to cover

- Some other item to cover

The meeting will be in #arctica on irc.freenode.net, 21:00 UTC.
```

### Step 2: Running the meeting

#### Start the meeting and set the topic

1. Join #arctica on irc.freenode.net.
2. Start the meeting with **#startmeeting** *some meeting name*. This will be the meeting name.
3. If the meeting has more than one topic loop over them with **#topic** *some topic name*, else leave the topic as is.
4. End the meeting with **#endmeeting**.

Once the meeting has ended an email will be sent out to the devs@lists.arctica-project.org mail list.

#### Asign items to the topic

- **#action** *some body will read the entire Internet*
  - If the specified nick says something during the meeting it will get the action assigned.
  - The task is recognized to the nick even if it doesn't write anything with the **#some** *nick* command.

- **#info** *To state some information*

- **#idea** *Announce some idea*

- **#link** *here is some {url} with useful information about about xxx*

- **#help** *Look for somebody who knows about xxx*

#### Meeting moderation

- Chair
  - The person who starts the meeting becomes the chair.
  - Those who become chair can guide the meeting.
  - Chairs can be added or removed with **#chair** *nick* and **#unchair** *nick*.

- The last item can be removed with **#undo**.

- **#agreed** *To agree on something* (only chairs can agree on items)
  - Mark something as agreed.

## History of meetings

You can find the history of all meetings at http://arctica-project.org/meetbot/arctica/log/ .
