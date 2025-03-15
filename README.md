# Using Special Filter Operators
<table border="1">
  <tr>
    <td>REQUEST</td>
    <td>QUERY</td>
    <td>PACKETS DISPLAYED</td>
    <td>DEMONSTRATION</td>
  </tr>
  <tr>
    <td>1.DNS Packets(no ICMP)</td>
    <td>dns and ! icmp</td>
    <td>52</td>
    <td><img src="https://github.com/user-attachments/assets/2a1be0be-30f8-4793-9cda-ff3fdf7fea30" alt="DNS Packet Screenshot" width="200"></td>
  </tr>
  <tr>
    <td>2.DNS including the word "foundation"(Regardless of case)</td>
    <td>dns matches "foundation" and ! icmp </td>
    <td>34</td>
    <td><img src="https://github.com/user-attachments/assets/18c7e066-05e9-46aa-a81a-a29eb5b39aa3" alt="DNS matches Screeshot" width="200"></td>
  </tr>
  <tr>
    <td>3.DNS requests for domains that do not have the word "foundation" </td>
    <td>dns and ! dns matches "foundation" and ! icmp</td>
    <td>18</td>
    <td><img src="https://github.com/user-attachments/assets/aff0a025-1215-494f-a275-1de52df7a235" ></td>
  </tr>
  <tr>
    <td>4.TCP port 443</td>
    <td>tcp.port in {443}</td>
    <td>885</td>
  </tr>
  <tr>
    <td>Row 6, Cell 1</td>
    <td>Row 6, Cell 2</td>
    <td>Row 6, Cell 3</td>
  </tr>
  <tr>
    <td>Row 7, Cell 1</td>
    <td>Row 7, Cell 2</td>
    <td>Row 7, Cell 3</td>
  </tr>
  <tr>
    <td>Row 8, Cell 1</td>
    <td>Row 8, Cell 2</td>
    <td>Row 8, Cell 3</td>
  </tr>
  <tr>
    <td>Row 9, Cell 1</td>
    <td>Row 9, Cell 2</td>
    <td>Row 9, Cell 3</td>
  </tr>
  <tr>
    <td>Row 10, Cell 1</td>
    <td>Row 10, Cell 2</td>
    <td>Row 10, Cell 3</td>
  </tr>
  <tr>
    <td>Row 11, Cell 1</td>
    <td>Row 11, Cell 2</td>
    <td>Row 11, Cell 3</td>
  </tr>
    <tr>
    <td>Row 12, Cell 1</td>
    <td>Row 12, Cell 2</td>
    <td>Row 12, Cell 3</td>
  </tr>
</table>


![Screenshot 2025-03-15 030215]()
