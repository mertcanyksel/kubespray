# kubespray
Inventory -> kebespray -> hosts.yaml -> internal ip ler ile ve makına adlarını değiş
vars.yaml -> private_key_file uznatısını pem dosyasına göre ayarla
ansible-playbook -i inventory/kubespray/hosts.yaml  --become --become-user=root cluster.yml
