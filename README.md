# Assignment
Bootstrap table using JSON data

1. Include bootstrap for styling from booystrapcdn.
https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" 

2.Include bootstrap table css for the table.
https://unpkg.com/bootstrap-table@1.16.0/dist/bootstrap-table.min.css"

3. Include jquery and other required files for bootstrap.
4. Include javascript file for bootstrap table.
5. Declare variable named mydata in order to make JSON string into javascript object.
5. using jquery select 'table' element for bootstraptable and print mydata.

 <script type="text/javascript"> 
	$(document).ready(function () {  
	$('table').bootstrapTable({ 
		data: mydata 
  }); 
	}); 
  </script>
