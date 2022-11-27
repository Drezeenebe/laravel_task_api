<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Sobre el Proyecto

Proyecto desarrollado con Laravel para crear una API basica de tareas, con las consultas basicas de un CRUD.

Lista de rutas para consumir API:

<table>
    <thead>
        <th>Method</th>
        <th>URI</th>
        <th>Action</th>
    </thead>
    <tbody>
        <tr>
            <td>GET|HEAD</td>
            <td>api/tasks</td>
            <td>Get all task </td>
        </tr>
        <tr>
            <td>POST</td>
            <td>api/tasks</td>
            <td>Create a task </td>
        </tr>
        <tr>
            <td>GET|HEAD</td>
            <td>api/tasks/{id_task}</td>
            <td>Show a task </td>
        </tr>
        <tr>
            <td>PUT|PATCH</td>
            <td>api/tasks/{id_task}</td>
            <td>Update a task </td>
        </tr>
        <tr>
            <td>DELETE</td>
            <td>api/tasks/{id_task}</td>
            <td>Delete a task </td>
        </tr>
    </tbody>
</table>


