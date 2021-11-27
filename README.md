# Jarkom-Modul-4-B14-2021
Achmad Akbar Irwanda (05111940000138)

![image](https://user-images.githubusercontent.com/45300477/143682492-8ccdd45c-066c-485d-9f49-8db39452a463.png)

## Pembagian Subnet
![Pembagian Subnet](https://user-images.githubusercontent.com/45300477/143682641-85aeebb9-317f-42fe-ae7e-9254bfd85965.jpg)

## VLSM
| Subnet        | Jumlah IP     | Netmask |
| ------------- |:-------------:| -------:|
| A3            |	2             |	/30     |
| A4            |	2             |	/30     |
| A5            |	2             |	/30     |
| A7            |	2             |	/30     |
| A12           |	2             |	/30     |
| A14           |	2             |	/30     |
| A10           |	13            |	/28     |
| A6            |	101           |	/25     |
| A13           |	252           |	/24     |
| A9            |	502           |	/23     |
| A1            |	1001          |	/22     |
| A2            |	701           |	/22     |
| A8            |	521           |	/22     |
| A15           |	721           |	/22     |
| A11           |	2021          |	/21     |
| Total         |	5845          |	/19     |

[link tabel](https://docs.google.com/spreadsheets/d/1qdc6B-auOzIDDhrJK4Aj8uZVcVPeZ67pQGjgLScgIrE/edit?usp=sharing)

Dari tabel tersebut bisa didapatkan tabel seperti berikut:
![Pohon vlsm](https://user-images.githubusercontent.com/45300477/143683104-8bc408e1-95b4-40c0-bbec-39cc84679888.jpg)

Sehigga kemudian dapat ditentukan NetworkID, NetMask dan Broadcast Address dari masing-masing subnet.
<table cellspacing="0" border="0">
	<colgroup width="64"></colgroup>
	<colgroup width="133"></colgroup>
	<colgroup width="134"></colgroup>
	<tr>
		<td rowspan=3 height="106" align="center">A1</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.4.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.252.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.7.255</td>
	</tr>
	<tr>
		<td rowspan=3 height="106" align="center">A2</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.8.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.252.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.11.255</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A3</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.252</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.3</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A4</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.4</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.252</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.7</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A5</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.8</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.252</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.11</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A6</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.128</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.128</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.255</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A7</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.12</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.252</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.15</td>
	</tr>
	<tr>
		<td rowspan=3 height="106" align="center">A8</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.12.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.252.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.15.255</td>
	</tr>
	<tr>
		<td rowspan=3 height="106" align="center">A9</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.2.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.254.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.3.255</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A10</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.32</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.240</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.47</td>
	</tr>
	<tr>
		<td rowspan=3 height="106" align="center">A11</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.24.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.248.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.31.0</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A12</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.16</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.252</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.19</td>
	</tr>
	<tr>
		<td rowspan=3 height="106" align="center">A13</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.1.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.1.255</td>
	</tr>
	<tr>
		<td rowspan=3 height="93" align="center">A14</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.0.20</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.255.252</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.0.23</td>
	</tr>
	<tr>
		<td rowspan=3 height="106" align="center">A15</td>
		<td align="left">NetworkID</td>
		<td align="center">10.14.16.0</td>
	</tr>
	<tr>
		<td align="left">NetMask</td>
		<td align="center">255.255.252.0</td>
	</tr>
	<tr>
		<td align="left">Broadcast Address</td>
		<td align="center">10.14.19.255</td>
	</tr>
</table>

## CIDR
Pertama, bedakan jauhnya subnet yang satu dengan yang lain

![cidr0](https://user-images.githubusercontent.com/45300477/143683656-2bf4d3e8-34b4-4dd5-b066-f4d783aab118.jpg)

Sehingga didapat bahwa A15 adalah subnet terjauh. Sehingga pertama penggabungan adalah subnet A13 dengan A15 (B1).
Berikutnya yang terjauh adalah subnet berwarna merah yang dapat digabung, yaitu A6 & A11 dan B1 dengan A14. Begitu seterusnya sampai seluruhnya berada dalam satu subnet.

![Pembagian CIDR](https://user-images.githubusercontent.com/45300477/143683763-d5c265d6-9de4-42cd-b537-e3b2566db73e.jpg)

Dapat dilihat bahwa subnet besar memiliki netmask /15, sehingga dalam pohon cidr yang terbesar adalah /15 seperti berikut:
![jarkom-CIDR](https://user-images.githubusercontent.com/45300477/143683921-35fc31b9-0670-4c68-ae53-90767757a722.png)

## Konfigurasi:
1. Konfigurasi router
Setiap router dikonfigurasikan menurut kabel yang terhubung terhadap subnet. Misal Foosha dan Water7 adalah subnet A4. Maka interface 1/0 pada Foosha dan interface 1/0 pada  Water7 harus memiliki IP di antara NID (10.14.0.4) dan Broadcast Address (10.14.0.7) (eksklusif/tidak termasuk). Berikut adalah contoh pada Foosha yang mengarah Water7.

![image](https://user-images.githubusercontent.com/45300477/143684595-cb57681a-24ae-4691-aaf7-3ffd1fea6d59.png)

Sementara pada Water7

![image](https://user-images.githubusercontent.com/45300477/143684727-36aff0c9-0ac0-45b3-a2ca-d9b70450554e.png)

2. Konfigurasi Host
Atur IP sesuai subnet yang telah ditentukan sebelumnya (di antara NID dan Broadcast Address). Misalnya Blueno (A1):

![image](https://user-images.githubusercontent.com/45300477/143684856-23cf63da-b60a-4987-836c-fe16100bb976.png)

Default gateway adalah IP yang digunakan Foosha pada interface 0/1. IP yang digunakan juga merupakan IP untuk A1. Hal ini berlaku pada semua PC.

## Routing
Routing adalah dengan mengatur tujuan (NID dan netmasknya) serta next hop untuk mengatur titik yang harus dilalui sebelum paket sampai ke tujuan.
