## ClamAV

ClamAV is an open source antivirus engine for detecting trojans, viruses, malware & other malicious threats.

## ClamAV Docker Images

This image is based on Alpine Linux.

### Usage

Example:

    docker run -d --name clamav -p 3310:3310 geekduck/clamavd


link:

    docker run -d --name clamav geekduck/clamavd
    docker run -d --link clamav:clamav some_app
