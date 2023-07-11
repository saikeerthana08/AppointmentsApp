In this project, I build an **Appointments App**.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/appointments-app-output.gif" alt="appointments app output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/appointments-app-sm-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/appointments-app-lg-output.png)

</details>

### Completion Instructions

<details>
<summary>Functionalities added</summary>
<br/>

The app has the following functionalities

- Initially, the list of appointments should be empty and the title input and date input should be empty
- When non-empty values are provided for the title and date and the **Add** button is clicked,
  - A new appointment is added to the list of appointments
  - The value inside the input elements for title and date is updated to their initial values
- When the **Star** on an appointment is clicked, the appointment is starred
- The status of the **Starred** filter is updated by clicking on it
- When the **Starred** filter is active, all the starred appointments are filtered and displayed
- When the **Starred** filter is inactive, the list of all appointments is displayed
</details>

<details>
<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/appointments-app-component-breakdown-structure.png" alt="component structure" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>

<details>
<summary>Implemented Files</summary>
<br/>

Used these files to complete the implementation:

- `src/components/Appointments/index.js`
- `src/components/Appointments/index.css`
- `src/components/AppointmentItem/index.js`
- `src/components/AppointmentItem/index.css`
</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/appointments-app/appointments-img.png](https://assets.ccbp.in/frontend/react-js/appointments-app/appointments-img.png) alt should be **appointments**
- [https://assets.ccbp.in/frontend/react-js/appointments-app/star-img.png](https://assets.ccbp.in/frontend/react-js/appointments-app/star-img.png)
- [https://assets.ccbp.in/frontend/react-js/appointments-app/filled-star-img.png](https://assets.ccbp.in/frontend/react-js/appointments-app/filled-star-img.png)

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #9796f0; width: 150px; padding: 10px; color: black">Hex: #9796f0</div>
<div style="background-color: #fbc7d4; width: 150px; padding: 10px; color: black">Hex: #fbc7d4</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #171f46; width: 150px; padding: 10px; color: white">Hex: #171f46</div>
<div style="background-color: #8b5cf6; width: 150px; padding: 10px; color: black">Hex: #8b5cf6</div>
<div style="background-color: #b5b7c4; width: 150px; padding: 10px; color: black">Hex: #b5b7c4</div>
<div style="background-color: #9897f0; width: 150px; padding: 10px; color: black">Hex: #9897f0</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>
