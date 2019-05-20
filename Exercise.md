# FileSystemsImplementersPerspective

## 1 FAT

### 1 a.)

The disk has 250 000 000 000 bits free space and with a 1000 bit block size the disk hast 250 000 000 000 / 1000 blocks which equals 250 000 000 blocks.

### 1 b.)

The FAT has to have space for 250 000 000 entries.

### 1 c.)

An table entry has the size of 32 Bit

### 1 d.)

The FAT now has a size of 250 000 000 * 32 = 8 000 000 000 which equals 1 GB because we need to go from Bit to Byte.

## 2 Random Access on Files

### 2 a.)

The Position 107 843 590 is in the trippel i-node adress 2 which references a double i-node and the adress on the 158 position references a single i-node where the needet Position is in the Block which is referenced by the 55 adress.

### 2 b.)

Because the FAT System uses a method where Files are linked behind each other so if we want to get to the position 107 843 590 we need to go trough 105 308 Blocks.

## 3 UFS (i-node) File Size

32 Bit -> 4 Byte

Methode 1 4KB block size:

One block fits 1024 entrys
trippel i-node 1024^3

/

Methode 2 1KB block size:

One block fits 256 entrys
trippel i-node 256^3

## 4 UFS File Size

### 4 a.)

5GB -> 5368709120 Byte

512 Byte block size
5GB / 512 Bytes = 40 trippel i-nodes

1024 Byte block size
5GB / 1024 Bytes = 5 trippel i-nodes

### 4 b.)

512 block size
12GB / 512 = 96 trippel i-nodes

1024 block size
12GB / 1024 = 12 trippel i-nodes
