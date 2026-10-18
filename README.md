# Running an ASL Class on Zoom

What breaks when you teach a class in American Sign Language on Zoom, what we do about it at the American Society for Deaf Children, and what we have asked Zoom to change. Written from running weekly ASL classes for several hundred learners at a time, with interpreters, across multiple Zoom accounts.

If you only read one line: Zoom decides who is on screen by listening for audio. A class taught in sign language has no audio from the teacher. So the platform keeps showing the wrong person.

## The core problem

Active speaker view, focus mode, and cloud recordings all choose the main video by detecting who is making sound. In a class delivered in ASL, the person making sound is the voicing interpreter, who is translating the teacher for hearing participants. The person teaching is silent. Zoom puts the interpreter on the main stage and pushes the signing instructor into a small tile or off screen entirely.

Three places this bites:

- **Active speaker and focus mode in the main room.** Learners see the voicer, not the signer. The host can fix this with Spotlight, which forces one person onto everyone's screen. That works, as long as the host remembers and nobody else gets spotlighted.
- **Breakout rooms.** Co-hosts running breakout rooms cannot spotlight anyone. Participants can pin the signer for their own view, but every participant has to know how, do it themselves, and do it again each time they move rooms. In a class of beginners, many of them children, that does not happen. We have watched participants leave breakout rooms and come back to the main room to report that they could not see the teacher.
- **Cloud recordings.** Cloud recording follows the active speaker or the spotlight, and it only records the main room. Pinned views are never recorded. A recording of an ASL class in speaker view shows the voicing interpreter for most of the session. Breakout rooms are not cloud-recorded at all.

Microsoft Teams has a Sign Language View that keeps up to two signers at a fixed size and position regardless of who is speaking. That is the behavior we need.

## What we do about it (the workarounds)

These are the settings and habits that keep classes running. Each one costs staff time or money, which is why we are also asking Zoom to fix the underlying behavior.

### Before the class

- One Zoom account per classroom (we run several named classroom accounts) so the host of each class controls spotlight and recording for that room.
- A separate tech host who is not the teacher and not the interpreter. Their only job is spotlight, pins, breakout rooms, recording, and the chat. A teacher cannot sign and manage Zoom at the same time.
- Register attendees so you can send the link, a how-to-pin reminder, and the accessibility arrangements in the same email, in English and Spanish.
- Zoom's Sign Language Interpretation View (host assigns interpreters to a sign language channel; participants open a separate resizable interpreter window) is worth turning on for the main room. It does not help in breakout rooms.

### During the class

- Spotlight the signing instructor in the main room from the first minute. If there is more than one signer, Add Spotlight for each (Zoom allows up to nine).
- Ask participants to pin the instructor and the interpreter for their own view, and show them how in the first two minutes. Desktop: hover the video, click the three dots, Pin. Mobile: long press the video, Pin.
- Keep breakout rooms short and small, put an interpreter or assistant teacher in each one, and tell participants before they go that they will need to pin the signer again once they arrive.
- Have the tech host watch the chat for "I can't see the teacher" and move people as needed.
- One person speaks or signs at a time. Interpreters and teachers get a break every 20 to 30 minutes in anything over an hour.

### Recording

- Record to the cloud in **gallery view**, not speaker view, so the signer is at least present in the recording at equal size with everyone else.
- For a recording that follows the signer, run a **parallel local recording** on a second device where someone manually controls the view. This ties up a device and a person for the whole class.
- Breakout room content is not captured by cloud recording. If it matters, a local recording from inside the room is the only option.

## What we have asked Zoom for

ASDC filed a formal accessibility feature request with Zoom in December 2025, escalated it in May and June 2026, and met with Zoom's accessibility and product teams in July 2026 to demonstrate the behavior live. The requests, in priority order:

1. **Signer-priority active speaker.** A sign language mode or toggle that lets the host identify the primary communicator as a signer, so active speaker view, focus mode, and cloud recordings follow visual signing activity instead of audio. Microsoft Teams' Sign Language View is the reference point.
2. **Spotlight for co-hosts in breakout rooms**, so a signer can be put on everyone's screen without each participant pinning.
3. **Cloud recording of breakout rooms.**

As of October 2026 Zoom has not committed to a timeline. We will update this page when anything changes.

## Why this matters beyond one nonprofit

Zoom is used by school districts, universities, hospitals, and government agencies that carry their own obligations under ADA Titles II and III, Section 504, Section 508, and the CVAA. When the platform defaults away from the signer, every one of those organizations inherits the barrier. A Deaf student in a breakout room who cannot see the teacher is an access failure for the school, not just an inconvenience for the student.

## Contributing

If you run sign language classes or meetings on Zoom and have a workaround we have missed, or data on how often this happens, open an issue or a pull request. If you work at Zoom, you know where to find us.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0). Credit the American Society for Deaf Children.
