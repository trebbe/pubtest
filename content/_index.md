---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: portfolio
    id: by-application
    content:
      title: Publications by Application
      filters:
        folders:
          - application
      buttons:
        - name: All
          tag: '*'
        - name: Brain
          tag: brain
        - name: Muscle
          tag: muscle
    design:
      columns: '3'
      view: card
      flip_alt_rows: false    
  - block: portfolio
    id: by-device
    content:
      title: Publications by Device
      filters:
        folders:
          - device
      buttons:
        - name: All
          tag: '*'
        - name: EEG
          tag: eeg-project
        - name: fnirs
          tag: fnirs
    design:
      columns: '3'
      view: card
      flip_alt_rows: false
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'


---
