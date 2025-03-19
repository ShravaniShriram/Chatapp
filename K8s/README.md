# For start the serviec use this command and & is used for that application should run in the backend 
kubectl port-forward service/backend -n chat-app 5001:5001 --address=0.0.0.0 &


#  This service for frontend
kubectl port-forward service/frontend -n chat-app 8021:80 --address=0.0.0.0
