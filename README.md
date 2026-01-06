# A Geometric Information Theory of Harmonic Perception

**A Unified Mathematical Framework for Predicting Emotional Qualities of Musical Structures**

---

## Abstract

We present a novel theoretical framework that models human perception of musical harmony as a three-dimensional geometric space derived from first principles. Building on the observation that listeners exhibit consistent emotional responses to scales, modes, and chords, we propose that these responses are mathematically predictable through three independent axes: **Brightness** (clustering position relative to root), **Balance** (gap variance), and **Complexity** (interval diversity). 

Central to our framework is the *Urinal Principle*—a maximal-distribution heuristic that explains the prevalence of the diatonic scale and the construction of optimal chord voicings. We further propose that musical structures function as information-carrying signals, where deviations from uniform interval patterns constitute the semantic content perceived by listeners.

This framework reduces centuries of music-theoretical tradition to geometric and information-theoretic primitives, enabling computational analysis and prediction of harmonic "feel" without reference to culturally-specific conventions.

**Keywords:** music cognition, harmony, information theory, geometric music theory, interval distribution, diatonic scale, chord perception

---

## 1. Introduction

### 1.1 The Problem of Musical Affect

Why does a minor chord sound "sad" and a major chord sound "happy"? Why do some scales feel "dark" while others feel "bright"? Traditional music theory offers descriptive taxonomies (major/minor, consonant/dissonant) but rarely provides *explanatory mechanisms* grounded in mathematical principles.

We argue that these affective qualities emerge from the geometric distribution of notes within the 12-tone equal temperament system, and that listeners unconsciously evaluate this distribution along multiple independent axes.

### 1.2 The 12-Tone Axiom

Our framework rests on a foundational simplification:

> **All music reduces to patterns within 12 semitones.**

Due to octave equivalence—the psychoacoustic phenomenon where pitches separated by an octave are perceived as fundamentally "the same"—we can model all harmonic relationships as positions on a circular space of 12 elements (the *pitch-class circle*).

This is the "assembly language" of Western music: the irreducible substrate upon which all harmony, melody, and scale structures are built.

### 1.3 Prior Work

Geometric approaches to music theory have precedent in the work of Tymoczko (2011) on voice-leading geometry and Callender et al. (2008) on generalized voice-leading spaces. Our contribution differs in focusing on *perceptual dimensions* rather than transformational relationships, and in explicitly connecting geometric properties to information-theoretic measures.

---

## 2. The Urinal Principle

### 2.1 Maximal Distribution as Optimization

Consider the following heuristic, which we term the *Urinal Principle*:

> **Given n positions to fill in a space of size 12, optimal placement maximizes the minimum distance between any two adjacent positions.**

This principle—analogous to the social behavior of maximizing personal space—explains why certain scales and chords are perceived as more "natural" or "pleasing" than others.

### 2.2 Application to the Diatonic Scale

The diatonic scale contains 7 notes distributed across 12 semitones. Its interval pattern is:

$$[2, 2, 1, 2, 2, 2, 1]$$

This is the *maximally even* distribution of 7 elements in 12 positions. No other 7-note scale achieves better gap uniformity. The two half-steps (1s) are positioned as far apart as possible (separated by 2 and 3 whole-steps respectively).

**Theorem 1:** *The diatonic scale is the unique 7-note scale that maximizes the minimum interval while maintaining exactly 2 interval types.*

### 2.3 Application to Chord Construction

Chord construction follows the same principle. Given a triad (3 notes in 12 positions):

| Chord | Gaps | Min Gap |
|-------|------|---------|
| Major (0,4,7) | 4, 3, 5 | 3 |
| Minor (0,3,7) | 3, 4, 5 | 3 |
| Diminished (0,3,6) | 3, 3, 6 | 3 |
| Augmented (0,4,8) | 4, 4, 4 | 4 |

The augmented triad achieves perfect uniformity (all gaps equal), while major and minor triads achieve near-optimal distribution.

---

## 3. The Three-Dimensional Harmonic Space

We propose that perceived harmonic quality can be mapped onto a three-dimensional space defined by independent geometric and information-theoretic measures.

### 3.1 Axis X: Brightness (Clustering Position)

**Definition:** Brightness measures the position of interval clustering relative to the designated root.

For modes of the diatonic scale:

| Mode | Pattern | First Intervals | Brightness |
|------|---------|-----------------|------------|
| Locrian | H-W-W-H-W-W-W | H, W | Darkest (−3) |
| Phrygian | H-W-W-W-H-W-W | H, W | Very Dark (−2) |
| Aeolian | W-H-W-W-H-W-W | W, H | Dark (−1) |
| Dorian | W-H-W-W-W-H-W | W, H | Neutral (0) |
| Mixolydian | W-W-H-W-W-H-W | W, W | Neutral+ (0) |
| Ionian | W-W-H-W-W-W-H | W, W | Bright (+1) |
| Lydian | W-W-W-H-W-W-H | W, W, W | Brightest (+2) |

**Principle:** Half-steps near the root create perceptual "tension" or "darkness." Whole-steps near the root create "openness" or "brightness."

**Formula (simplified):**
$$X = \sum_{i=1}^{n} w_i \cdot I_i$$

where $I_i$ is the interval at position $i$ from root, and $w_i$ is a weighting function that decreases with distance from root.

### 3.2 Axis Y: Balance (Gap Variance)

**Definition:** Balance measures the uniformity of interval distribution, independent of position.

**Formula:**
$$Y = 1 - \text{Var}(G)$$

where $G = [g_1, g_2, ..., g_n]$ is the vector of cyclic gaps between adjacent notes.

| Structure | Gaps | Variance | Balance |
|-----------|------|----------|---------|
| Augmented (0,4,8) | 4,4,4 | 0.00 | Maximum |
| Dim7 (0,3,6,9) | 3,3,3,3 | 0.00 | Maximum |
| Dom7 (0,4,7,10) | 4,3,3,2 | 0.50 | High |
| Major (0,4,7) | 4,3,5 | 0.67 | High |
| Add2 (0,2,4,7) | 2,2,3,5 | 1.50 | Medium |
| Cluster (0,1,2) | 1,1,10 | 18.0 | Minimum |

**Interpretation:** High-balance chords feel "complete" or "stable." Low-balance chords feel "leaning" or "unresolved."

### 3.3 Axis Z: Complexity (Interval Diversity)

**Definition:** Complexity measures the information content of the interval pattern, conceptualized as the number of distinct interval types or the entropy of the gap sequence.

**Formula (entropy-based):**
$$Z = -\sum_{k} p_k \log_2 p_k$$

where $p_k$ is the proportion of gaps of size $k$.

| Structure | Gaps | Distinct Types | Entropy | Complexity |
|-----------|------|----------------|---------|------------|
| Whole-tone | 2,2,2,2,2,2 | 1 | 0.00 | Minimum |
| Diatonic | 2,2,1,2,2,2,1 | 2 | 0.86 | Optimal |
| Harmonic Minor | 2,1,2,2,1,3,1 | 3 | 1.38 | High |
| Chromatic | 1,1,1,1,1,1,1,1,1,1,1,1 | 1 | 0.00 | Zero (noise) |

---

## 4. The Information-Theoretic Interpretation

### 4.1 Music as Modulated Signal

We propose a fundamental reframing:

> **Musical structures function as information-carrying signals. The "carrier wave" is uniform interval distribution; the "modulation" is deviation from uniformity.**

Consider the analogy to acoustic waveforms:

| Domain | Uniform (No Information) | Modulated (Information) |
|--------|--------------------------|-------------------------|
| Sound | Pure sine wave | Complex waveform with harmonics |
| Timbre | Tuning fork | Violin, guitar, voice |
| Scales | Whole-tone (2-2-2-2-2-2) | Diatonic (2-2-1-2-2-2-1) |
| Chords | Augmented (4-4-4) | Major (4-3-5), Minor (3-4-5) |

### 4.2 Irregularities as Semantic Content

The half-steps in the diatonic scale are not "imperfections"—they are the *information content*. Without them, the scale collapses to the whole-tone scale, which:

- Has no distinct modes (1 unique rotation)
- Provides no sense of "home" or "resolution"  
- Is described universally as "floaty" or "directionless"

The diatonic scale's two half-steps function like harmonics added to a fundamental frequency: they create richness, character, and meaning.

### 4.3 The Goldilocks Zone

Musical utility exists in a bounded region of complexity:

$$0 < Z < Z_{max}$$

| Complexity | Example | Perception |
|------------|---------|------------|
| Z ≈ 0 | Whole-tone, chromatic | Boring / Noise |
| Z ≈ 0.5 | Blues scale, bebop additions | Tension, mysterious, "searching" |
| Z ≈ 1 | Diatonic | Optimal richness |
| Z ≈ 1.5 | Harmonic minor | Exotic, "spicy" |
| Z > 2 | Random intervals | Chaotic, unparseable |

This parallels information theory: a signal with zero entropy carries no information; a signal with maximum entropy is indistinguishable from noise.

**The Harmonic Analogy:** Extending the wave metaphor, we can understand the Z-axis as describing the "harmonic content" of a musical structure:

| Zone | Wave Analogy | Perceptual Quality |
|------|--------------|-------------------|
| Z ≈ 0.5 | Fundamental with weak harmonic | Thin, yearning for fullness |
| Z ≈ 1 | Fundamental with balanced harmonics | Complete, satisfying |
| Z ≈ 1.5 | Fundamental with extra harmonics | Rich, almost overwhelming |

**The Tension Zone (Z ≈ 0.5):** Structures with Z ≈ 0.5 are "almost uniform, with one notable exception"—like a pure tone with a single faint overtone. This creates a sense of *incompleteness*: the ear detects structure but wants more. This is the harmonic space of jazz passing tones, blues "blue notes," and film score ambiguity. Composers seeking "interesting" rather than "resolved" sounds often operate in this zone.

**The Saturation Zone (Z ≈ 1.5):** Conversely, structures with Z > 1 contain "extra" interval types—like a fundamental overloaded with harmonics. The ear perceives richness bordering on excess: exotic, spicy, almost too much information. Harmonic minor's augmented second is the classic example—it adds a third interval type (3) that creates distinctive "Eastern" or "Spanish" color.

---

## 5. Empirical Predictions

Our framework generates testable predictions:

### 5.1 Prediction 1: Mode Brightness Ordering

Listeners presented with the seven diatonic modes will consistently rank their "brightness" or "happiness" in the order:

$$\text{Locrian} < \text{Phrygian} < \text{Aeolian} < \text{Dorian} < \text{Mixolydian} < \text{Ionian} < \text{Lydian}$$

This ordering follows directly from the position of half-steps relative to root.

### 5.2 Prediction 2: Chord Stability Ratings

Listener ratings of chord "stability" or "completeness" will correlate inversely with gap variance:

$$r(\text{Stability}, Y) > 0.7$$

### 5.3 Prediction 3: Optimal Tetrad Selection

Given a major triad {0, 4, 7}, listeners will prefer extensions that minimize gap variance:

| Extension | Result | Gaps | Variance | Predicted Preference |
|-----------|--------|------|----------|----------------------|
| +9 (pos 10) | 0,4,7,10 | 4,3,3,2 | 0.50 | High |
| +6 (pos 9) | 0,4,7,9 | 4,3,2,3 | 0.50 | High |
| +2 (pos 2) | 0,2,4,7 | 2,2,3,5 | 1.50 | Medium |
| +4 (pos 5) | 0,4,5,7 | 4,1,2,5 | 2.50 | Low (violates min-gap) |

### 5.4 Prediction 4: Scale Preference

When asked to construct novel scales, composers will converge toward distributions that:
1. Maximize minimum gap (urinal principle)
2. Minimize gap variance (balance)
3. Maintain 2-3 distinct interval types (optimal complexity)

---

## 6. The Unified Model

### 6.1 The Three-Dimensional Harmonic Space

```
                              Z+ : COMPLEX (rich)
                              ▲   Harmonic Minor (saturated)
                              │
                              │   Diatonic (optimal)
                              │
                              │   Blues, Bebop (thin, yearning)
                              │
    X− : DARK ◄───────────────┼───────────────► X+ : BRIGHT
    (Locrian, Phrygian)       │                 (Lydian, Ionian)
                              │
                              ▼
                              Z− : SIMPLE (boring)
                              Whole-tone, Dim7, Aug


           Y− : UNBALANCED ◄──┼──► Y+ : BALANCED
           (leaning, clusters)│    (evenly distributed)
                              │
              Add2, Sus4      │    Augmented, Dim7
              (unstable)      │    (stable but boring)
```

### 6.2 Formalization

For any pitch-class set $S = \{s_1, s_2, ..., s_n\}$ with designated root $s_1$:

1. **Compute gaps:** $G = [g_1, g_2, ..., g_n]$ where $g_i = (s_{i+1} - s_i) \mod 12$

2. **Brightness (X):** 
$$X(S) = \sum_{i=1}^{k} \alpha^{i-1} \cdot g_i$$
where $\alpha < 1$ weights early intervals more heavily.

3. **Balance (Y):**
$$Y(S) = \frac{1}{1 + \text{Var}(G)}$$

4. **Complexity (Z):**
$$Z(S) = H(G) = -\sum_{v \in \text{unique}(G)} \frac{c_v}{n} \log_2 \frac{c_v}{n}$$
where $c_v$ is the count of gap value $v$.

### 6.3 The Perceptual Sweet Spot

The most commonly used musical structures cluster in a specific region:

| Structure | X | Y | Z |
|-----------|---|---|---|
| Ionian mode | +1 | High | 0.86 |
| Aeolian mode | −1 | High | 0.86 |
| Major triad | +1 | High | 1.0 |
| Minor triad | −1 | High | 1.0 |
| Dom7 | +0.5 | High | 1.0 |
| Pentatonic | 0 | High | 0.97 |

These structures share: **moderate brightness, high balance, and moderate complexity.**

---

## 7. Discussion

### 7.1 Explaining Traditional Rules

Our framework provides explanations for traditionally "axiomatic" rules:

| Traditional Rule | Geometric Explanation |
|------------------|----------------------|
| "Avoid parallel fifths" | Creates gap-variance spikes in voice leading |
| "Resolve tritones" | Tritone creates maximum local tension (gap asymmetry) |
| "Seventh chords resolve down" | Restores balance by eliminating smallest gap |
| "Sus4 replaces the 3rd" | Coexistence violates min-gap constraint |

### 7.2 The Special Case of Locrian

Locrian is universally avoided in tonal music. Our framework explains why:

1. **Darkest mode** (X = minimum): Half-step immediately above root
2. **Missing P5**: The 5th degree is diminished (6 semitones, not 7)

The perfect fifth is the second-most-important interval after the unison (per urinal principle: 7 semitones ≈ half of 12). Its absence fundamentally destabilizes the mode.

### 7.3 Cultural Universality vs. Specificity

Our framework predicts certain cross-cultural universals:
- Preference for balanced distributions (high Y)
- Moderate complexity preference (middle Z)
- Root-relative tension perception (X axis)

Cultural variation enters through:
- Preferred region of the X axis (dark vs. bright aesthetic)
- Tolerance for lower Y (acceptance of "unresolved" structures)
- Complexity preferences (Z range)

---

## 8. Implications for Music Technology

### 8.1 Automated Composition Analysis

Any musical passage can be analyzed by computing (X, Y, Z) trajectories over time, revealing:
- Emotional arc (X movement)
- Tension/resolution patterns (Y movement)
- Complexity modulation (Z movement)

### 8.2 Generative Music Systems

Composition algorithms can target specific regions of (X, Y, Z) space to achieve desired emotional qualities without relying on rule-based heuristics.

### 8.3 Music Education

The framework provides a unified explanation for "why" traditional rules exist, replacing memorization with understanding.

---

## 9. Conclusion

We have presented a three-dimensional geometric framework for understanding harmonic perception:

1. **The Urinal Principle** explains optimal note distribution
2. **Brightness (X)** captures dark-to-bright emotional gradation via clustering position
3. **Balance (Y)** captures stability via gap variance
4. **Complexity (Z)** captures richness via interval diversity

Crucially, we reframe musical structures as **information-carrying signals**, where irregularities in interval patterns constitute the semantic content perceived by listeners. The diatonic scale's prevalence is not arbitrary—it represents the optimal encoding of musical information: balanced enough for coherence, complex enough for meaning.

This framework reduces music theory's descriptive complexity to geometric and information-theoretic primitives, offering both explanatory power and computational tractability.

---

## References

Callender, C., Quinn, I., & Tymoczko, D. (2008). Generalized voice-leading spaces. *Science*, 320(5874), 346-348.

Tymoczko, D. (2011). *A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice*. Oxford University Press.

Shannon, C. E. (1948). A mathematical theory of communication. *Bell System Technical Journal*, 27(3), 379-423.

Clough, J., & Douthett, J. (1991). Maximally even sets. *Journal of Music Theory*, 35(1/2), 93-173.

---

## Appendix A: Chord and Scale Coordinates

### A.1 Common Chords

| Chord | Semitones | X (Bright) | Y (Balance) | Z (Complex) |
|-------|-----------|------------|-------------|-------------|
| Major | 0,4,7 | +2 | 0.60 | 1.00 |
| Minor | 0,3,7 | −2 | 0.60 | 1.00 |
| Diminished | 0,3,6 | −3 | 0.33 | 0.92 |
| Augmented | 0,4,8 | +1 | 1.00 | 0.00 |
| Sus4 | 0,5,7 | 0 | 0.33 | 0.92 |
| Maj7 | 0,4,7,11 | +2 | 0.40 | 1.00 |
| Dom7 | 0,4,7,10 | +1 | 0.67 | 1.00 |
| Min7 | 0,3,7,10 | −1 | 0.67 | 1.00 |
| Dim7 | 0,3,6,9 | −3 | 1.00 | 0.00 |
| Maj6 | 0,4,7,9 | +2 | 0.67 | 1.00 |
| Min6 | 0,3,7,9 | −1 | 0.67 | 1.00 |

### A.2 Common Scales

| Scale | Intervals | X (Bright) | Y (Balance) | Z (Complex) |
|-------|-----------|------------|-------------|-------------|
| Ionian | 2,2,1,2,2,2,1 | +2 | 0.81 | 0.86 |
| Dorian | 2,1,2,2,2,1,2 | 0 | 0.81 | 0.86 |
| Phrygian | 1,2,2,2,1,2,2 | −3 | 0.81 | 0.86 |
| Lydian | 2,2,2,1,2,2,1 | +3 | 0.81 | 0.86 |
| Mixolydian | 2,2,1,2,2,1,2 | +1 | 0.81 | 0.86 |
| Aeolian | 2,1,2,2,1,2,2 | −2 | 0.81 | 0.86 |
| Locrian | 1,2,2,1,2,2,2 | −4 | 0.81 | 0.86 |
| Harmonic Minor | 2,1,2,2,1,3,1 | −2 | 0.64 | 1.38 |
| Melodic Minor | 2,1,2,2,2,2,1 | −1 | 0.81 | 0.86 |
| Whole-tone | 2,2,2,2,2,2 | 0 | 1.00 | 0.00 |
| Pentatonic Maj | 2,2,3,2,3 | +1 | 0.80 | 0.97 |

---

## Appendix B: Mathematical Definitions

### B.1 Cyclic Gap Vector

For pitch-class set $S = \{s_1, s_2, ..., s_n\}$ ordered by pitch:

$$G(S) = [(s_2 - s_1), (s_3 - s_2), ..., (s_1 + 12 - s_n)]$$

### B.2 Gap Variance

$$\text{Var}(G) = \frac{1}{n}\sum_{i=1}^{n}(g_i - \bar{g})^2$$

where $\bar{g} = \frac{12}{n}$ (the mean gap for n notes in 12 semitones).

### B.3 Gap Entropy

$$H(G) = -\sum_{v \in V} p_v \log_2 p_v$$

where $V$ is the set of unique gap values and $p_v = \frac{|\{g_i : g_i = v\}|}{n}$.

---

*Manuscript prepared: January 2026*
