# Frontend RBAC components

Remove RBACs resources to disable service discovery for frontend.

If `sourcegraph-frontend.RoleBinding` was created previously, you will need to add the `/components/disable/service-discovery/role-binding` component to remove it,
testing to see if this works for a branch name that previously existed
