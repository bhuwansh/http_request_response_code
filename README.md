# HTTP request method
<table>
  <tr>    <th>Method</th>     <th>Defination</th>   </tr>
  <tr>      <td>GET</td><td>The GET method is used to retrieve information from the given server using a given URI. Requests using GET should only retrieve data and should have no other effect on the data</td>   </tr>
  
  <tr><td>POST</td><td>A POST request is used to send data to the server, for example, customer information, file upload, etc. using HTML forms.</td></tr>
 
  <tr><td>HEAD</td><td>Same as GET, but transfers the status line and header section only.</td></tr>
  
  <tr><td>PUT</td><td>Replaces all current representations of the target resource with the uploaded content.</td></tr>
  
  <tr><td>DELETE</td><td>Removes all current representations of the target resource given by a URI.</td></tr>
  
  <tr><td>OPTIONS</td><td>Describes the communication options for the target resource.</td></tr>
  
  <tr><td>CONNECT</td><td>Establishes a tunnel to the server identified by a given URI.</td></tr>

</table>

# HTTP response status codes
<ul> 
  <li>Informational responses ( 100 – 199 )</li>
  <li>Successful responses ( 200 – 299 )</li>
  <li>Redirection messages ( 300 – 399 )</li>
  <li>Client error responses ( 400 – 499 )</li>
  <li>Server error responses ( 500 – 599 )</li>
</ul>


# 1XX : HTTP Information code
<table>
  <tr>    <th>code </th>     <th>Defination</th>   </tr>
  <tr>     <td>100</td><td>Continue</td>    </tr>
  <tr>     <td>101</td><td>Switching Protocols</td>    </tr>
  <tr>     <td>102</td><td>Processing</td>    </tr>
  <tr>     <td>103</td><td>Checkpoint</td>    </tr>
  <tr>     <td>122</td><td>request-URI too Long</td>    </tr>

</table>
  
  
  # 2XX : HTTP Successful code
<table>
  <tr>    <th>code </th>     <th>Defination</th>   </tr>
  <tr>     <td>200</td><td>OK</td>    </tr>
  <tr>     <td>201</td><td>created</td>    </tr>
  <tr>     <td>202</td><td>Accepted</td>    </tr>
  <tr>     <td>203</td><td>Non-Authoritative Information</td>    </tr>
  <tr>     <td>204</td><td>No Content</td>    </tr>
  <tr>     <td>205</td><td>Reset Content</td>    </tr>
  <tr>     <td>206</td><td>Partial Content</td>    </tr>
  <tr>     <td>207</td><td>Multi-status</td>    </tr>
  <tr>     <td>208</td><td>Already reported</td>    </tr>
  <tr>     <td>226</td><td>IM Used</td>    </tr>
</table>
  
  # 3XX : HTTP Redirection code
<table>
  <tr>    <th>code </th>     <th>Defination</th>   </tr>
  <tr>     <td>300</td><td>Multiple Choices</td>    </tr>
  <tr>     <td>301</td><td>Moved Permanently</td>    </tr>
  <tr>     <td>302</td><td>Found</td>    </tr>
  <tr>     <td>303</td><td>See Other</td>    </tr>
  <tr>     <td>304</td><td>Not Modified</td>    </tr>
  <tr>     <td>305</td><td>Use Proxy</td>    </tr>
  <tr>     <td>306</td><td>Switch Proxy</td>    </tr>
  <tr>     <td>307</td><td>Temporary Redirect</td>    </tr>
  <tr>     <td>308</td><td>Permanent Redirect</td>    </tr>
  
</table>

  # 4XX : HTTP Client Error code
<table>
  <tr>    <th>code </th>     <th>Defination</th>   </tr>
  <tr>     <td>400</td><td>Bad Request</td>    </tr>
  <tr>     <td>401</td><td>Unauthorized</td>    </tr>
  <tr>     <td>402</td><td>Payment Required </td>    </tr>
  <tr>     <td>403</td><td>Forbidden</td>    </tr>
  <tr>     <td>404</td><td>Not Found</td>    </tr>
  <tr>     <td>405</td><td>Method Not Allowed</td>    </tr>
  <tr>     <td>406</td><td>Not Acceptable</td>    </tr>
  <tr>     <td>407</td><td>Proxy Authentication Required</td>    </tr>
  <tr>     <td>408</td><td>Request Timeout</td>    </tr>
  <tr>     <td>409</td><td>Conflict</td>    </tr>
  <tr>     <td>410</td><td>Gone</td>    </tr>
   <tr>     <td>411</td><td>Length Required</td>    </tr>
   <tr>     <td>412</td><td>Precondition Failed</td>    </tr>
   <tr>     <td>413</td><td>Payload Too Large</td>    </tr>
   <tr>     <td>414</td><td>URI Too Long</td>    </tr>
   <tr>     <td>415</td><td>Unsupported Media Type</td>    </tr>
   <tr>     <td>416</td><td>Range Not Satisfiable</td>    </tr>
  <tr>      <td>417</td><td>Expectation Failed</td>    </tr>
   <tr>     <td>418</td><td>I'm a teapot</td>    </tr>
     <tr>     <td>421</td><td>Misdirected Request</td>    </tr>
   <tr>     <td>422</td><td>Unprocessable Entity </td>    </tr>
   <tr>     <td>423</td><td>Locked </td>    </tr>
   <tr>     <td>424</td><td>Failed Dependency </td>    </tr>
   <tr>     <td>425</td><td>Too Early </td>    </tr>
  <tr>      <td>426</td><td>Upgrade Required</td>    </tr>
   <tr>     <td>428</td><td>Precondition Required</td>    </tr>
     <tr>     <td>429</td><td>Too Many Requests</td>    </tr>
   <tr>     <td>431</td><td>Request Header Fields Too Large</td>    </tr>
   <tr>     <td>451</td><td>Unavailable For Legal Reasons</td>    </tr>
  
</table>

# 5XX : HTTP Server Error code
<table>
  <tr>    <th>code </th>     <th>Defination</th>   </tr>
  <tr>     <td>500</td><td> Internal Server Error</td>    </tr>
  <tr>     <td>501</td><td> Not Implemented</td>    </tr>
  <tr>     <td>502</td><td>Bad Gateway</td>    </tr>
  <tr>     <td>503</td><td>Service Unavailable</td>    </tr>
  <tr>     <td>504</td><td>Gateway Timeout</td>    </tr>
  <tr>     <td>505</td><td>HTTP Version Not Supported</td>    </tr>
  <tr>     <td>506</td><td>Variant Also Negotiates</td>    </tr>
  <tr>     <td>507</td><td>Insufficient Storage </td>    </tr>
  <tr>     <td>508</td><td>Loop Detected </td>    </tr>
    <tr>     <td>510</td><td> Not Extended</td>    </tr>
    <tr>     <td>511</td><td> Network Authentication Required</td>    </tr>
</table>
