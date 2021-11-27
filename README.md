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

