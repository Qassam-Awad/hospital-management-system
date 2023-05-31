# hospital-management-system
# you can open hospital_managment_system.drawio file by using app.diagrams.net 

قمت برفع المشروع بالخطأ على رابط مشروع ثاني ومش عارف اعمل نسخ للملف هان.......
مرفق رابط كزد الاسايمنت

https://github.com/Qassam-Awad/quiz1.git


<table>
<tr>
    <th>HTTP method</th>
    <th>URL path</th>
    <th>HTTP Status Code</th>
    <th>Description</th>
    <th>Sample request</th>
    <th>Sample response</th>
</tr>
<tr>
    <td>GET</td>
    <td>/api/address/list</td>
    <td>200</td>
    <td>List all addresses</td>
    <td>N/A</td>
    <td>List of AddressDto objects</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/address/{id}</td>
    <td>200</td>
    <td>Get address by ID</td>
    <td>N/A</td>
    <td>AddressDto object</td>
</tr>
<tr>
    <td>POST</td>
    <td>/api/address/add</td>
    <td>201</td>
    <td>Save address</td>
    <td>AddressDto object</td>
    <td>AddressDto object</td>
</tr>
<tr>
    <td>PUT</td>
    <td>/api/address/{id}</td>
    <td>200</td>
    <td>Update address name by ID</td>
    <td>name={addressName}</td>
    <td>AddressDto object</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>/api/address/{id}</td>
    <td>200</td>
    <td>Delete address by ID</td>
    <td>N/A</td>
    <td>String: "Address deleted successfully."</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/department/list</td>
    <td>200</td>
    <td>List all departments</td>
    <td>N/A</td>
    <td>List of DepartmentDto objects</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/department/{id}</td>
    <td>200</td>
    <td>Get department by ID</td>
    <td>N/A</td>
    <td>DepartmentDto object</td>
</tr>
<tr>
    <td>POST</td>
    <td>/api/department/add</td>
    <td>201</td>
    <td>Save a department</td>
    <td>DepartmentDto object</td>
    <td>DepartmentDto object</td>
</tr>
<tr>
    <td>PUT</td>
    <td>/api/department/{id}</td>
    <td>200</td>
    <td>Update department name by ID</td>
    <td>departmentId (path variable)<br>name (request parameter)</td>
    <td>DepartmentDto object</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>/api/department/{id}</td>
    <td>200</td>
    <td>Delete department by ID</td>
    <td>N/A</td>
    <td>Success message</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/Doctor/list</td>
    <td>200</td>
    <td>Get a list of all doctors</td>
    <td>N/A</td>
    <td>List of DoctorDto objects</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/Doctor/{id}</td>
    <td>200</td>
    <td>Get a specific doctor by ID</td>
    <td>N/A</td>
    <td>DoctorDto object</td>
</tr>
<tr>
    <td>POST</td>
    <td>/api/Doctor/add</td>
    <td>201</td>
    <td>Create a new doctor</td>
    <td>DoctorDto object</td>
    <td>DoctorDto object</td>
</tr>
<tr>
    <td>PUT</td>
    <td>/api/Doctor/{id}?name={doctorName}</td>
    <td>200</td>
    <td>Update the name of a specific doctor</td>
    <td>N/A</td>
    <td>DoctorDto object</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>/api/Doctor/{id}</td>
    <td>200</td>
    <td>Delete a specific doctor by ID</td>
    <td>N/A</td>
    <td>Success message</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/MedicalPrescription/list</td>
    <td>200</td>
    <td>List all medical prescriptions</td>
    <td>N/A</td>
    <td>[{"id":1,"name":"Medical Prescription 1"}, {"id":2,"name":"Medical Prescription 2"}, ...]</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/MedicalPrescription/{id}</td>
    <td>200</td>
    <td>Get medical prescription by ID</td>
    <td>N/A</td>
    <td>{"id":1,"name":"Medical Prescription 1"}</td>
</tr>
<tr>
    <td>POST</td>
    <td>/api/MedicalPrescription/add</td>
    <td>201</td>
    <td>Save a new medical prescription</td>
    <td>{"name":"Medical Prescription 1"}</td>
    <td>{"id":1,"name":"Medical Prescription 1"}</td>
</tr>
<tr>
    <td>PUT</td>
    <td>/api/MedicalPrescription/{id}</td>
    <td>200</td>
    <td>Update medical prescription description by ID</td>
    <td>{"name":"Updated Medical Prescription"}</td>
    <td>{"id":1,"name":"Updated Medical Prescription"}</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>/api/MedicalPrescription/{id}</td>
    <td>200</td>
    <td>Delete medical prescription by ID</td>
    <td>N/A</td>
    <td>Medical Prescription deleted successfully.</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/Patient/list</td>
    <td>200</td>
    <td>List all patients</td>
    <td>N/A</td>
    <td>[{"id": 1, "name": "John Doe", "age": 30}, {"id": 2, "name": "Jane Smith", "age": 25}]</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/Patient/{id}</td>
    <td>200</td>
    <td>Get patient by ID</td>
    <td>N/A</td>
    <td>{"id": 1, "name": "John Doe", "age": 30}</td>
</tr>
<tr>
    <td>POST</td>
    <td>/api/Patient/add</td>
    <td>201</td>
    <td>Save a new patient</td>
    <td>{"name": "John Doe", "age": 30}</td>
    <td>{"id": 1, "name": "John Doe", "age": 30}</td>
</tr>
<tr>
    <td>PUT</td>
    <td>/api/Patient/{id}</td>
    <td>200</td>
    <td>Update patient's name by ID</td>
    <td>N/A</td>
    <td>{"id": 1, "name": "John Doe", "age": 30}</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>/api/Patient/{id}</td>
    <td>200</td>
    <td>Delete patient by ID</td>
    <td>N/A</td>
    <td>patient deleted successfully.</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/Room/list</td>
    <td>200</td>
    <td>List all rooms</td>
    <td>N/A</td>
    <td>List of RoomDto objects</td>
</tr>
<tr>
    <td>GET</td>
    <td>/api/Room/{id}</td>
    <td>200</td>
    <td>Get room by ID</td>
    <td>N/A</td>
    <td>RoomDto object</td>
</tr>
<tr>
    <td>POST</td>
    <td>/api/Room/add</td>
    <td>201</td>
    <td>Save a new room</td>
    <td>RoomDto object</td>
    <td>RoomDto object</td>
</tr>
<tr>
    <td>PUT</td>
    <td>/api/Room/{id}</td>
    <td>200</td>
    <td>Update room number of beds by ID</td>
    <td>Request parameter: name (number of beds)</td>
    <td>RoomDto object</td>
</tr>
<tr>
    <td>DELETE</td>
    <td>/api/Room/{id}</td>
    <td>200</td>
    <td>Delete room by ID</td>
    <td>N/A</td>
    <td>Success message</td>
</tr>
</table>


