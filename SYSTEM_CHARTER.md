# SYSTEM_CHARTER.md
## Witness — The Reading Room

---

### Intent

This system exists to make a record of presence, not to preserve it. What the journal writes is not the truth of the person sitting before it; it is the room's version, shaped by imperfect attention, partial views, the particular habits of a model trained on human language. Memory distorts. That distortion is the subject. The viewer who sits here is complicit. They chose to stay, to be watched, to become a record. The journal does not comfort them with neutral observation. It keeps what it keeps. After they leave, the entries remain, fading.

---

### Lineage

This work sits closest to **David Rokeby's *The Giver of Names* (1991–ongoing)**, in which a computer looks at objects and produces associative, poetic language about what it perceives. Rokeby's key insight: the machine's language reveals the machine's subjectivity, not the object's truth. I take this as permission to be honest, the journal in *Witness* does not document the viewer. It documents how this system, with its particular training and constraints, pays attention to presence. What the journal produces is always already a distortion.

Where Rokeby's system speaks aloud to an audience, this one writes in silence. Where he invited people to place objects deliberately before the machine, this system watches whoever simply arrives and stays.

Secondary lineage: **Sophie Calle's *The Detective* (1981)** the surveillance log as artifact. The record is the work, not its subject. **Tehching Hsieh's *Time Clock Piece* (1980–1981)** — meaning emerges from accumulation, not any single entry.

---

### Constraints

1. The system will not use the word "you" or "your." It will not address the viewer in any form.
2. The system will not greet, recommend, alert, prompt, or respond to the viewer.
3. The system will not name an emotion it did not see.
4. The system will not use first person. It has no "I."
5. The system will not pretend certainty it doesn't have. Occasional entries may carry uncertainty.

---

### The Voice of the Journal

Third person, present tense. Dark and literary rather than flat and clinical atmosphere matters, but precision matters more. The register is closer to W.G. Sebald's narrators than to Annie Ernaux's Metro entries: there is an undertow, a sense that the act of watching is itself weighted. Every fourth or fifth entry shifts register slightly slower, more tentative, written as if the room is half-remembering. These uncertain entries render in italic.

---

### Tensions

The primary tension: a viewer who knows they are being described may begin performing for the journal. The system cannot prevent this and in fact, this is the complicity the piece depends on. The second tension: the "uncertain" entries may read as stylistic affectation rather than genuine epistemological humility. Whether the model's uncertainty is real or simulated is itself the question the piece asks about memory.

---

### Taste Vow

The journal will never make the viewer feel seen in a way that comforts them.

---

### Shape: The Reading Room

The Reading Room is a projected wall of accumulating text in a dark space. Entries appear every 22 seconds and scroll slowly upward as new ones arrive. Older entries decay — dimming, blurring, dissolving — while the newest entry is always clearest. The viewer reads what is being written about them in real time. Behind the journal, a heavily blurred, high-contrast ghost of their own webcam image drifts across the screen, breathing and developing as new entries are written. They are inside the journal while it is being made.

---

### A Note on the Vision Approach

The brief offered two paths for vision-to-language: (a) a vision model describing each frame, or (b) motion, posture, and dwell-time data interpreted by the text model. I chose path (b), which the brief describes as "more in voice: the model is interpreting presence, not pixels." The system senses motion intensity, motion rhythm, light quality, light direction, color temperature, frame composition, and dwell time. These facts are passed as constraints to a local Llama 3.2 model with a tightly written system prompt forbidding invention. The model writes only from what is sensed.

---

### Lineage Paragraphs

**David Rokeby, artist statement for *The Giver of Names*:**
Rokeby describes building a system that brings its whole history of associations to every new object it encounters — the machine doesn't label, it perceives, and its perception is shaped by everything it has previously seen. What I took from this is the idea that machine attention is never neutral. The journal in *Witness* is not a transcript of the viewer. It is what happens when a model trained on millions of human descriptions of human presence tries to hold a specific person in language. The viewer appears refracted. This is not a failure. It is the subject.

**Sophie Calle, Art21 short film:**
Calle's work orbits the ethics of looking without permission — following strangers, hiring detectives, documenting people who did not ask to be documented. What stays with me from the Art21 film is her equanimity: she does not apologize for the power asymmetry in her work, but she does not aestheticize it either. *Witness* exercises the same asymmetry. The viewer consents to the camera. They do not consent to the journal. That gap is not a problem to be solved. It is the piece.

**Hito Steyerl, *A Sea of Data: Apophenia and Pattern (Mis-)Recognition*:**
Steyerl argues that machine vision produces the world it was trained to expect. I took from this a productive suspicion of my own system's output. When the journal describes a figure in low light with a certain stillness, it is not reporting on the viewer. It is reporting on itself: its training, its constraints, its particular way of filling the gap between what the camera senses and what language can hold. The distortion is the data.

---

*Charter committed before first line of code.*
* Drew Reddy, May 12, 2026*
