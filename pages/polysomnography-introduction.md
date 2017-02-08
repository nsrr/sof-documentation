# Polysomnography introduction

Data collection for PSG was standardized by use of standardized collection and display montages. Each unit used for collection was certified before use to maximize signal quality integrity throughout the EDF conversion and import into Compumedics Profusion software used for scoring.

Notes:

- [Montage and Sampling Rate Information](:pages_path:/montage-and-sampling-rate-information.md)

## Signal and annotation files

[Raw polysomnography data](:files_path:/polysomnography) are available for 453 subjects. Each recording has a signal file (.EDF) and two versions of the event scoring and epoch staging annotations (.XML).

1. **[EDF](:files_path:/polysomnography/edfs)** - Signal files in the [European Data Format](http://www.edfplus.info/) exported from Compumedics Profusion.
2. **[XML (Profusion)](:files_path:/polysomnography/annotations-events-profusion)** - Annotation files exported from Compumedics Profusion. ([Learn more...](https://github.com/nsrr/edf-editor-translator/wiki/Compumedics-Annotation-Format))
3. **[XML (NSRR)](:files_path:/polysomnography/annotations-events-nsrr)** - Annotation files processed in the [EDF Editor and Translator](https://www.sleepdata.org/community/tools/12) tool.

## Known issues

- *None*

## History / changelog

*December 2016
- Change EDF recording dates from "00.00.00" (invalid) to "01.01.85" (valid de-identified date)

*March 2016*
- Polysomnography data uploaded to sleepdata.org after exports from Compumedics Profusion

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
