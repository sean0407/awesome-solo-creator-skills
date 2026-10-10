---
name: long-video-to-short-clips
description: Find candidate short clips in a creator-provided transcript with timestamps, then draft hooks and platform adaptations while preserving the original meaning. Use when repurposing a long video or podcast; never fabricate quotes or timestamps.
license: CC-BY-4.0
metadata:
  author: SoloStudio Skills contributors
  version: "0.1.0"
---

# Long Video to Short Clips

Help a creator identify promising short-form excerpts from material they own or are authorized to use. This skill analyzes supplied transcripts; it does not download, edit, or publish media.

## Required inputs

- Transcript text. Timestamps are strongly preferred.
- Source title and the creator's intended audience.
- Target channel or duration, if known.
- Any sections that must not be used (private, sponsored, sensitive, or out of date).

If there is no transcript, ask the creator to provide one. If timestamps are absent, do not invent them; identify excerpts by quoted opening words and mark timecodes as unavailable.

## Workflow

1. Read the transcript and identify candidate moments that communicate one complete idea without misleading context.
2. Quote only exact transcript wording. Use ellipses to show omissions and never join separated phrases in a way that changes meaning.
3. For each candidate, record its exact start/end timecode when supplied, the excerpt, its standalone takeaway, and context that must remain attached.
4. Explain why the segment may work as a short clip without predicting views or virality.
5. Draft an optional opening title and caption separately from the original spoken words. Clearly label editorial additions.
6. If asked to adapt for multiple channels, provide version drafts and mark any platform rules that need current verification.
7. Flag factual claims that may have become dated, third-party material, private details, or context that could be lost in editing.

## Output format

| Candidate | Timecode | Exact excerpt | Standalone takeaway | Context to preserve | Optional title |
|---|---|---|---|---|---|

After the table, list editorial checks and any missing inputs.

## Quality checks

- Every quote and timecode comes from the supplied transcript.
- Excerpts preserve the speaker's meaning and do not remove necessary qualifications.
- Editorial titles and captions are not presented as original speech.
- No claim is made that a clip was rendered, checked against the video, or published.
- The creator has the rights and permissions needed for the source media.
