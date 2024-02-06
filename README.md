# Decentralization_Workshop2

Instructions
Download the Torrent package.
![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/effc320a-c8c4-4bee-89e9-91cdb0448dea)

Check installation.
Ensuring the tool is correctly installed helps avoid any unnecessary troubleshooting later.

torrent --version
Torrent commands.
These commands allow you to interact with the BitTorrent network, including downloading, creating, seeding, and inspecting torrents.

torrent <magnet link OR path to .torrent file>

  Download a torrent from a magnet link or torrent file.

torrent create <directory OR file> {-o outfile.torrent}

  Create a torrent file from a directory or file.

  If an output file isn't specified with `-o`, the torrent file will be
  written to stdout.

torrent seed <torrent file>

  Seed a torrent file.

torrent info <torrent file>

  Print information about a .torrent file to stdout as JSON.
Questions
Q1 - Create a torrent containing this image.
Q2 - Now copy the image to a new directory named partition1 and create a torrent of this folder. What do you observe?
Q3 - Copy the partition1 folder and then generate the associated torrent. What do you observe?
