# Proyecto 1: Arquitectura Escalable en AWS

## Objetivo
Implementar una arquitectura básica y escalable utilizando Amazon EC2, Auto Scaling y Elastic Load Balancer para simular una aplicación web con alta disponibilidad.

## Servicios utilizados
- Amazon EC2
- Auto Scaling Group
- Elastic Load Balancing (Application Load Balancer)
- Amazon VPC
- Security Groups

## Descripción de la arquitectura
- El tráfico de usuarios ingresa a través de un Load Balancer.
- El Load Balancer distribuye las solicitudes entre múltiples instancias EC2.
- El Auto Scaling Group ajusta automáticamente la cantidad de instancias según la carga.
- Las instancias están distribuidas en múltiples zonas de disponibilidad.

## Estado
🔧 En progreso
