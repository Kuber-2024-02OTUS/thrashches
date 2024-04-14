# Домашнее задание 2


### Цель:
1) Научиться создавать и конфигурировать Replicaset,
   Deployment длā своего приложения;
2) Научиться управлять обновлением своего приложениā;
3) Научиться исполþзовать механизм Probes для проверки
   работоспособности своих приложений.
### Запуск проекта

Для работы приложения необходимо интернет соединение.

```bash
kubectl apply -f kubernetes-controllers/namespace.yaml
kubectl apply -f kubernetes-controllers/deployment.yaml
```