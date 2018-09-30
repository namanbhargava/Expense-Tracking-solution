# Expense-Tracking-solution
<p>For User registration, REST API end points</p>
<br>
<table>
  <tr>
    <th>HTTP Method</th>
    <th>End Point</th>
    <th>Autheticated Endpoint</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>GET</td>
    <td>/ </td>
    <td>Yes	</td>
    <td>Get current time</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/user/register</td>
    <td>No</td>
    <td>Create account for user</td>
  </tr> 
 </table>
<br>
  
<p>For expense management , REST API end points</p>
<table>
  <tr>
    <td>GET</td>
    <td>/transaction</td>
    <td>Get all transactions for a user</td>
  </tr>
  <tr>
    <td>POST</td>
    <td>/transaction</td>
    <td>Add transaction for a user</td>
  </tr>
  <tr>
    <td>PUT</td>
    <td>/transaction/{id}</td>
    <td>Update a particular transaction</td>
  </tr>
  <tr>
    <td>DELETE</td>
    <td>/transaction/{id}</td>
    <td>Delete a transaction</td>
  </tr>
  </table>
