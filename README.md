# Data

Some of the data relevant for the [Rags2Riches](https://research-software-directory.org/projects/rags2riches) project. More project data can be found on [osf.io](https://osf.io/p4w65/files/osfstorage).
We use `git lfs` to handle the large files. Check `.gitattributes`.

## bhic-98144.json.gz

Metadata for 98,144 deceased persons with scans in the Memories van Successie of the Brabant province. Data originates from the website [bhic.nl](https://www.bhic.nl/onderzoeken/hulp-bij-onderzoek/memories-van-successie). Data include an identifier, the name of the deceased person, the death date, the place of death and the url of the scan. Example record:

    {
      "identifier": "e8efc7f8-f22b-a950-b67d-7073d8d1b374",
      "person_name": "Petronella Dielis",
      "death_date": "1901-05-01",
      "death_place": "Leende",
      "scan_uri": "https://images.memorix.nl/bhic/download/fullsize/3f803bd6-44d4-872f-4969-98b0659ebe4a.jpg"
    }

## scan-alignment.tar.gz

From Auke's e-mail. Includes the alignment.csv, images, and `scan_alignment.md` (renamed to `README.md`).
Untar with `tar -zxf scan-alignment.tar.gz`.
