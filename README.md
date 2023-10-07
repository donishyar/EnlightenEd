# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


-- Setup the frontend

step 1 ------  npm install ------  installing dependencies

step 2 ------ npm run dev ------   starting the frontend




----------------------------------------------------> run these commands in separate terminals




--------cmd-------------

-- Setup the backend 

step 1---- installing python virtual environment 

        py -m venv env .

step 2---- running python virtual environment

    Scripts\activate.bat

step 3---- install server.py requirements 

    pip install uvicorn fastapi tortoise-orm
    pip install tortoise-orm[fastapi]

Finally for running the server 

    uvicorn app:app --reload 

server will run on     http://127.0.0.1:8000