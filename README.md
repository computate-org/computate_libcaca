
# Install the prerequisite applications, powertools and libmodplug

- https://github.com/computate-org/computate_powertools
- https://github.com/computate-org/computate_libmodplug

# Install the libcaca ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_libcaca

# Clone the libcaca ansible role. 
git clone git@github.com:computate-org/computate_libcaca.git ~/.ansible/roles/computate.computate_libcaca

# Change into the libcaca ansible role directory. 
cd ~/.ansible/roles/computate.computate_libcaca
```

# Run the libcaca ansible playbook to install libcaca locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
