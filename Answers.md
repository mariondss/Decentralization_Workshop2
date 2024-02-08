# Decentralization_Workshop2

## Torrent

Download the Torrent package.

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/effc320a-c8c4-4bee-89e9-91cdb0448dea)

Check installation.

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/0db22502-d1ef-42ed-9be8-ee7cb46470bf)

### Questions
Q1 - Create a torrent containing this image.

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/7d21c57a-4768-4cc8-aeda-5492555a37d6)

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/131b324a-b577-467c-8708-799b853cc001)

Its magnet link is : magnet:?xt=urn:btih:c651f121b4108191f1e10c41f031ae02c58c7bc1&dn=Chaton.jpeg

When I add the magnet link on utorrent I get the initial kitten image

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/b3ffcfe4-e8fe-4440-9783-d21ed8f5d4be)


Q2 - Now copy the image to a new directory named partition1 and create a torrent of this folder. What do you observe?

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/785778dd-3cf3-47b3-ba63-7284f7a11ac2)

Note that in "info" a files section has been added containing information about the different files that the folder contains. In addition, the hash is different for the Chaton file and the folder containing the same file.


Q3 - Copy the partition1 folder and then generate the associated torrent. What do you observe?

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/b28423a8-947e-486e-92de-3958a56d1cdc)

Only the hash is modified.


## IPFS

Installation IPFS CLI 

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/d18b8639-7033-4152-85ea-f53e0079d326)

Installation IPFS Desktop client.

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/50aade1f-dfc4-40f2-819f-3230f3aa2858)


### Questions
Be sure to have download IPFS Desktop and IPFS CLI before starting this section

Q1 - Upload the previous image to IPFS.

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/a4a92a3a-3741-4ea2-b032-17841796707f)

CID : QmeJaufp9seXCpHMFwxX53P3oRQW8Ny1DduCXAxebEwxv7

Q2 - Now upload partition1 to IPFS. What do you observe compared to the torrent part?

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/c9b4b64a-d7cb-49e7-bf8d-150fa8e8f724)

IPFS uses a distributed hash table to locate content, meaning that each node in the network stores a portion of the overall index, allowing for efficient content discovery without the need for central servers or trackers. On the other hand, torrents rely on trackers to coordinate peers, facilitating the initial connection between users sharing the same file. The size and the hash are different for the same folder partition1.

Q3 - Copy the partition1 folder and then generate the associated torrent. What do you observe?

![image](https://github.com/mariondss/Decentralization_Workshop2/assets/114142047/451fef62-e383-4066-84ac-b2c1426b9ce0)

After recovering the partition1 folder on ipfs and then generating its associated torrent, we notice that only the hash and the name (which is the CID) are different


## Create your first decentralized website

Upload files on IPFS using Pinata


Leverage P2P to create a website hosted decentralizely.
In this section we will host a website directly from IPFS. Plus we will automaticly deploy website modification to production using GitHub action.

IPFS Pinata deploy action
