# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


purushottammalbishoye/devsecops-cicd

echo "$(kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}")"
echo 'SFZ4OHdVTUVwTUk5YlNTLQ==' | base64 --d

helm install aws-load-balancer-controller eks/aws-load-balancer-controller -n kube-system --set clusterName=testing-cluster --set serviceAccount.create=false --set serviceAccount.name=aws-load-balancer-controller --version 1.13.0

look for a file named kubeseal-install.sh for kubeseal installation
sealed secrets is in mysealedsecret.yaml