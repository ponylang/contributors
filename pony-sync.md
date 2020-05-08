# Pony Sync

The Pony Sync is a weekly meeting where Pony contributors discuss topics related to Pony, including recently added or modified issues.

## Running the Pony Sync

The Pony Sync takes place as a [Zoom](https://zoom.us) call. In order to run the Pony Sync you must have Zoom installed, and be logged in as `ponylang.main@gmail.com`. A list of recently modified issues can be generated using the [pony-sync-helper](https://github.com/ponylang/pony-sync-helper) application; this list should be pasted into the `sync` stream in Zulip, in a topic whose name is the date of the meeting in US date format (for example May 12, 2020 would be "5/12/2020").

### Prerequisites

In order to run the Pony Sync meeting you will need:

1. A GitHub account
2. A GitHub personal access token for running the `pony-sync-helper` program
3. The [`pony-sync-helper`](https://github.com/ponylang/pony-sync-helper) program
4. [Zulip](https://zulipchat.com/) and a Zulip account
5. A 1Password account that is connected to the Pony 1Password account
6. [Zoom](https://zoom.us)
7. The Zoom password for the `ponylang.main@gmail.com` account, which is available in the Pony 1Password vault
8. Access to the Pony Sync recording account on [nearlyfreespeech.net](https://nearlyfreespeech.net) (for access, contact Sean T. Allen via private message on Zulip)
9. A program for transfering files via `scp`

### Steps

1. Generate the list of issues for discussion using the `pony-sync-helper` program. The program repo contains instructions for building and running it.
2. Using the `ponylang.main@gmail.com` account, log into the Zoom meeting a few minutes before the official start time.
3. When you feel that there are enough people in the meeting to start, announce that you will be recording the meeting and give participants a few seconds to stop talking. Give a countdown to when you will start recording so that noone is caught unaware.
4. Start recording the meeting in Zoom.
5. Begin the meeting by stating that this is the Pony Sync meeting, giving the date, and giving everyone in the room a chance to introduce themselves.
6. After the introduction the meeting runner can set the agenda and proceed with the meeting.
7. When the meeting discussion has ended, stop recording and announce that you have stopped recording.
8. The recording of the meeting will be written to disk when you leave the meeting.
9. Use SCP to copy the meeting recording to the `r` directory of the Pony account on [nearlyfreespeech.net](https://nearlyfreespeech.net). The file should be called `DATE.m4a`, where `DATE` is the date in YYYY\_MM\_DD format(for example May 12, 2020 would be `2020_05_12.m4a`).
10. Put a note in [the Zulip topic for the sync](https://ponylang.zulipchat.com/#narrow/stream/190591-sync) announcing that the sync recording is available and points to the recording URL.
11. Add a comment to the "Last Week in Pony" issue (in the [ponylang/pony-website](https://github.com/ponylang/pony-website) repo) that also announces that the recording is available.
