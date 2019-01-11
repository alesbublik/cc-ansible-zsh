.PHONY: {{cookiecutter.name}}

init-{{cookiecutter.name}}: venv ;

cleanup-{{cookiecutter.name}}: ;

deploy-{{cookiecutter.name}}:
	venv/bin/ansible-playbook {{cookiecutter.name}}/playbook.yml -i inventory.ini
