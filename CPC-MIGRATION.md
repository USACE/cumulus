# Real Time Datafeeds

## High Priority

- [x] SNODAS
- [x] RTMA Air Temperature - ltia98 - (Archive Jan2011 - Mar2021)
- [x] RTMA Precip - leia98 - (Archive Jan2011 - Mar2021)
- [x] RTMA Air Temp (next gen ltia - 15min)
- [x] PRISM Early Airtemp Daily Max (July 2020 - Present)
- [x] PRISM Early Airtemp Daily Min (July 2020 - Present)
- [x] PRISM Early Precip Daily Total (July 2020 - Present)
- [ ] SNODAS-Interpolated
  - [ ] 1. SNODAS Masked (2004-2010)
  - [ ] 2. SNODAS-Interpolated Masked (2004-2010)
  - [ ] SNODAS-Interpolated Unmasked (2010-Present)
  - [ ] SNODAS-Interpolated Unmasked Realtime (Airflow DAG)
- [x] CBRFC Observed Precipitation (SPL)
  - [x] Airflow DAG to download from web
  - [x] Create Processing Script
  - [x] Add to Database Products & Deploy
- [x] High Resolution Rapid Refresh (HRRR)
  - Available on NOAA Big Data Project: https://noaa-hrrr-pds.s3.amazonaws.com
- [ ] NDFD Forecast Air Temperature (Days 1-3)
  - Available on NOAA Big Data Project: https://noaa-ndfd-pds.s3.amazonaws.com/index.html
- [ ] NDFD Forecast Air Temperature (Days 4-7)
  - Available on NOAA Big Data Project: https://noaa-ndfd-pds.s3.amazonaws.com/index.html

## Medium Priority

- [x] WPC 2.5KM Forecast Precipitation
- [x] Observed Precipitation
  - [x] LEIA98
  - [x] MRMS V12 QPE 01H Pass1
  - [x] MRMS V12 QPE 01H Pass2
- [ ] MRMS Air Temp
- [ ] NDFD Forecast Precipitation (Days 1-3)
  - Available on NOAA Big Data Project: https://noaa-ndfd-pds.s3.amazonaws.com/index.html
- [ ] NDFD Forecast Precipitation (Days 4-7)
  - Available on NOAA Big Data Project: https://noaa-ndfd-pds.s3.amazonaws.com/index.html
- [x] RTMA Precipitation - leia98

## Investigate Later

- [ ] Soil Moisture
- [ ] Datasets outside of CONUS
  - [ ] alaska, guam, hawaii, puertori
  - [ ] Canadian Border Datasets
- [ ] WPC 5km Forecast Precipitation
- [ ] ERA5-Land monthly averaged data from 1981 to present

# Notes:

- NOAA List of Big Data Program Datasets
  - https://registry.opendata.aws/collab/noaa/
  - https://www.noaa.gov/organization/information-technology/list-of-big-data-program-datasets#NWS
