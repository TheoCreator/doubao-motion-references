# Doubao motion references

Public motion reference files for character animation video generation.

## Rhea: approved equipped walk

- File: `videos/rhea/walk-equipped-approved-d5708aa79b0a1473.mp4`
- SHA-256: `d5708aa79b0a1473e5ffe4d628403987f52f495f3110325834a17b9130011f52`
- Original approved motion video; about five seconds at 24 fps. The approved game walk cycle uses source frames 69–91 inclusive (zero based).
- For an unequipped Rhea video, this file provides motion, foot sequence and timing. The separately selected body reference image provides identity, clothing, proportions and original colors.

## Direct URL

Use this [commit-pinned MP4 direct URL](https://raw.githubusercontent.com/TheoCreator/doubao-motion-references/54a5c1664d7af98d154fcb751d04a72f535446e4/videos/rhea/walk-equipped-approved-d5708aa79b0a1473.mp4). GitHub's file-view page is HTML and is not a video input URL. See `references.json` for file identity and motion scope.

Public anonymous download can be checked by comparing the MP4 header, byte count and SHA-256. This verifies file hosting; Doubao server access is separately verified by the generation task result.

## Upload policy

Publish only files explicitly designated for public motion reference. Keep filenames based on content hashes; add a new file when the contents change. Keep source provenance and motion timing in the manifest. This repository does not contain API credentials, generation request records, candidate batches or the source game project.
