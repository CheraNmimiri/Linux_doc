### Archive and Compression Commands

#### Tape Archive Format (tar)
For archiving files without compression by default, use:
```bash
tar
```

#### Multiplatform Compression Tool (zip)
For archiving and compressing files, utilize:
```bash
zip
```

#### Gzip Compression Tool
For efficient compression, consider using:
```bash
gzip
```

#### Better Compression Algorithm than Gzip (bzip2)
For more effective compression, try:
```bash
bzip2
```

### Commands

#### Create Tar Archives
To create tar archives, use:
```bash
tar -cf [archive-name]
```

#### Extract Tar Files
To extract tar files, employ:
```bash
tar -xf [tar-file]
```

#### Show Extracted Files or Directories List
To list extracted files or directories, execute:
```bash
tar -xvf [tar-file]
```

#### Compress Files and Folders with Zip
To compress files and folders using zip, run:
```bash
zip [zip-name] [file1] [file2] ...
```
### Tip
- **Zip Command Limitation**: Zip command cannot directly compress directories; it works only for files. To compress directories, use the `-r` option with the zip command.

#### Compress Directory with Zip
To compress a directory with zip, apply:
```bash
zip -r [zip-file-name] [directory-names]
```

#### Decompress Files and Folders
To decompress files and folders, use:
```bash
unzip [zip-file-name]
```

#### Show Content or File List in Zip File
To list contents or file list in a zip file, without decompressing, type:
```bash
unzip -l [zip-file-name]
```

#### Create Tar with Gzip Compression
To create tar with gzip compression, use:
```bash
tar -zcf [archive-name]
```

#### Extract Gzip File
To extract a gzip file, use:
```bash
gunzip [gzip-file-name]
```

#### Create Tar with Bzip2 Compression
To create tar with bzip2 compression, apply:
```bash
tar -jcf [archive-name]
```

#### Extract Bzip2 File
To extract a bzip2 file, execute:
```bash
bunzip2 [bzip-file-name]
```

