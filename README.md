# kubespray
Inventory -> kebespray -> hosts.yaml -> internal ip ler ile ve makına adlarını değiş
ansible.cfg -> private_key_file uznatısını pem dosyasına göre ayarla
ansible-playbook -i inventory/kubespray/hosts.yaml  --become --become-user=root cluster.yml

Eğer VS Code da değişikliğe izin vermiyorsa a+rwx chmod yetkisi verirsek düzelicektir. 
