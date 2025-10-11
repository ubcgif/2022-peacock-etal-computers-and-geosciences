---
title: MTH5 - An archive and exchangeable data format for magnetotelluric time series data
abstract: |
    Magnetotellurics (MT) is a passive electromagnetic geophysical method that measures variations in subsurface
    electrical resistivity. MT data are collected in the time domain and processed in the frequency domain to
    produce estimates of a transfer function representing the Earth’s electrical structure. Unfortunately, the MT
    community lacks metadata and data standards for time series data. As the community grows and findability,
    accessibility, interoperability, and reuse of digital assets (FAIR) data principles are enforced by government and
    funding agencies, a standard is needed for time series data. Presented here is a hierarchical data format (MTH5)
    that is logically formatted to how MT data are collected. Open-source Python packages are also described to
    read, write, and manipulate MTH5 files. These include a package to deal with metadata (`mt_metadata`) based
    on standards developed by the Working Group for Magnetotelluric Data Handling and Software assembled by
    the Incorporated Research Institutions for Seismology (IRIS), and mth5: a package to interact with MTH5 files
    that uses `mt_metadata`. Example code and workflows are presented.
---
