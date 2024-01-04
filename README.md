# MERN APP With K8S

### Objects Created
- **Namespace**
- **Secret**
- **ConfigMap**
- **Deployment**
- **Service**

## Details
- **Mongo-Express Credentials:**  
  Default username: `admin`  
  Default password: `pass`  
  Ensure to use these credentials when accessing the Mongo-Express endpoint.

- **K8S Configuration:**
  One deployment having 3 container frontend, backend and mongodb inside a single pod
  One deployemnt for Mongo-Express along with its service 

- **Frontend Configuration:**  
  If using the Vite-built MERN app, configure the `frontend/src/utils/constant.js` file accordingly.