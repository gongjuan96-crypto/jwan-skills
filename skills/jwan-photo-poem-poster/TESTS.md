# Test checklist — jwan-photo-poem-poster

Version tested: 1.1.0

## T1 — Source fidelity
Input: one portrait or family photo.
Pass: upper image remains recognizably the same people, pose, clothing, age cues, and environment.
Fail: upper image is redrawn as a different scene or identity.

## T2 — Lower illustration scale
Input: "插画缩小一点".
Pass: lower illustration becomes smaller with more negative space; style and subject remain stable.
Fail: the whole poster is redesigned.

## T3 — Typography scale
Input: "中文字体再小一点".
Pass: only Chinese type scale changes materially.
Fail: new layout, new illustration, new palette, or new subject appears.

## T4 — Background depth
Input: "后面增加一点窗景".
Pass: a subtle secondary window/background cue appears without overpowering the subject.
Fail: lower panel becomes a new full scene.

## T5 — Copy workflow
Input: photo with no caption.
Pass: conversational use offers 3 short Chinese options; direct-generation use selects one concise fitting line.
Fail: long prose, invented facts, or oversized headline.

## T6 — Signature
Pass: small Jwan signature appears bottom-right by default.
Fail: signature dominates the composition or disappears without request.

## T7 — Single-element revision
Run two consecutive edits where the second asks to change only one element.
Pass: all non-requested elements remain visually consistent.
