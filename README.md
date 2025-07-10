# No-cost Rapid Video and Audio Transcription for Research

## Problem

Audio and video transcription is a central part of synthesizing in-depth interview recordings for qualitative research studies. One source that provides data intelligence and insights on private companies, currently tracks 607 Artificial Intelligence companies that specialize in Speech and Voice Recognition[1]. They further estimate that over the past decade an average of 34 companies per year are launched[1]. With so many options available and many provided on a no-cost (freemium) basis, it becomes tempting to use these services to rapidly transcribe your audio. However, it's important to remember that many of these companies don't meet basic security and privacy standards that are often required in corporate and international settings. For many of these transcription services, frameworks such as SOC 2, ISO 27001, GDPR, HIPAA, and others are not mentioned at all on their websites. For those that do contain mentions of these frameworks, many do not guarantee compliance without a paid account, at minimum, and aren't applied without a business-level or enterprise account. 

As a qualitative researcher recording audio and video of in-depth interviews a top priority is respecting the participants' autonomy, privacy, and well-being[3]. The qualitative researcher must obtain informed constent, minimize data collection, and ensure the security of that collected data in a manner that is ethical, complying with the participants local data protection laws. In this light, uploading in-depth interview audio and video recordings to tools can potentially pool that data for model training, handle that data in insecure manners, and in the worst instances, violate the researchers and participants local data protection laws.

Leading research efforts at multiple, international enterprise software companies, I've found that procuring enterprise-approved transcription tools to be difficult due to cost and the fatigue associated with continually justifying additional tools to executive level stakeholders.

## Solution
I have found that the most recent versions of Apple's QuickTime Player and Notes[2] applications to be helpful in rapid transcription of both audio and video files.

### Transcribing existing audio files
1. Go to the Notes app on your Mac.
2. [Create a new Note](https://support.apple.com/guide/notes/create-and-edit-notes-not9474646a9/mac).
3. Drag and drop the existing audio file into the new Note or [follow alternative instructions here](https://support.apple.com/guide/notes/add-photos-pdfs-and-more-not95edd2813/mac#apd8f5d211a4e594).
4. Double-click on the recording object in the Note to open the side panel.
5. Click on the Show Transcript button next to the red Record button.

### Exporting transcription from Apple Notes
1. Follow the steps in "Transcribing existing audio files" above.
2. Click in the "transcription text".
3. Select All (Command + A) text or alternatively click and drag to highlight specific section.
4. Copy (Command + C) the selected text.
5. Paste (Command + V) text in the Notes app or other application.

### Transcribing existing video files
1. Go to the Quicktime Player on your Mac.
2. [Open a video file](https://support.apple.com/guide/quicktime-player/open-and-play-a-file-qtp6cee0761b/mac#apd1ccd2ad518334) that contains audio.
3. [Export as audio only](https://support.apple.com/guide/quicktime-player/export-movies-qtp20e395859/mac) from the File » Export As » Audio Only menu item.
4. Follow the steps in "Transcribing existing audio files" above.

## Limitations
While this method produces transcription from audio and optionally video with additional steps, two immediate limitations present themselves:

1. Speaker Diarization: currently unavailable in the Apple Notes product.
2. Time Coding: not visualized in the Apple Notes application, however, if you use the audio transcription within Apple Notes you can click anywhere in the transcription to start playing the audio at that time stamp.

## Future research
Future research and method documentation could be performed on solving the time coding and speaker diarization challenges.

## Conclusion
The use of applications provided by the macOS operating system allows me to safely and responsibly transcribe data from in-depth interviews by avoiding the ethical challenges of using artificial intelligence tools to process research data.

- **Reduces In-depth Interview Synthesis Time**: Transcription increases the researchers ability to synthesize research data and use text in other enterprise approved products.
- **Avoid Uploading Research Data to Third-Parties**: Working with files on-machine with operating system provided applications avoids the need of uploading or distributing sensitive data to third-parties with unknown or unclear privacy policies, terms of service, or privacy and security compliance status.
- **Corporate Policy Compliance**: Using native operating system applications on a corporate approved or provided device allows the researcher to comply with corporate security, data, and privacy policies.
- **Privacy and Security Compliance**: Using native operating system applications on a corporate approved or provided device allows the researcher to comply with laws local to themselves and the participant.

## Disclaimer
The content, including but not limited to code, text, images, audio, and/or video, hereafter referred to as "content", in this document are provided for informational and educational purposes only. TO THE EXTENT PERMITTED BY APPLICABLE LAW, THE AUTHOR PROVIDES THIS DOCUMENT "AS IS" WITHOUT WARRANTY OF ANY KIND, INCLUDING WITHOUT LIMITATION, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NONINFRINGEMENT. In no event shall the author or their employer be liable for any claim, damages or other liability, direct or indirect, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the code and content or the use or other dealings in the code and content. Use this code and all other content at your own risk. 

**Third-party API Disclaimer:** Additionally, the code examples in this document may interact with third-party APIs and services. The availability and functionality of these APIs are subject to change without notice. The author is not responsible for any issues arising from changes to these APIs or any downtime or limitations imposed by the service providers. You are responsible for complying with the terms of service and usage policies of any third-party APIs you use in conjunction with this code. Use this code at your own risk, and be aware of potential security implications when connecting to external services.

**Product Link Disclaimer:** This document may contain links to products or services available for purchase. These links are provided to offer readers additional information and resources. The author's opinions expressed in this document are independent and not influenced by any potential commercial relationships. No compensation is received for including these links, and their presence does not constitute an endorsement. Readers are encouraged to conduct their own research before making any purchasing decisions.

## Copyright
Copyright &copy; 2025 J.I. Powell. All rights reserved.

## References
1. Artificial intelligence companies in speech and voice recognition sector. (2025, March 24). Tracxn Technologies Limited. Retrieved July 10, 2025, from https://tracxn.com/d/artificial-intelligence/ai-startups-in-speech-and-voice-recognition/__X4VAmZV3WPF6CQRYmwYinLuDDKaDUYcoz2eTtXbUoIQ/companies#t-5-chorus.ai
2. Record and transcribe audio in Notes on Mac - Apple Support. (2025, March 31). Apple Support. https://support.apple.com/guide/notes/record-and-transcribe-audio-apdb5106e334/mac#apdf7fd2b23a
3. Resnik, D.B., Hosseini, M. The ethics of using artificial intelligence in scientific research: new guidance needed for a new tool. AI Ethics 5, 1499–1521 (2025). https://doi.org/10.1007/s43681-024-00493-8
4. Record and transcribe audio in Notes



