---
resources:
- name: Photo name 1
  params:
    button_text: Button text
    button_url: https://example.com
    description: Photo description. If you want to add your own link, specify button_text and button_url here.
    order: blue
  src: 3x2_photo.png
- name: Photo with EXIF
  params:
    description: This photo has EXIF info that is automatically extracted. Only JPG and TIFF files supports EXIF. If the automatically extracted time is incorrect, use "timestamp" field to supply your own time.
    order: 1
    timestamp: 2020-01-01 19:45
  src: 3x2_with_exif.jpg
- name: Panorama
  params:
    description: Use the "title" field on top of this file to specify a series name for a stylized appearance. It is hidden if "title" is unspecified.
    order: 3
  src: landscape_panorama.png
- name: Portrait
  params:
    description: Some description 2.
    order: 4
  src: portrait.png
- name: Square
  params:
    description: Some description 4.
    order: 5
  src: square.png
title: Series A
---
