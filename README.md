COMANDOS EJECUTADOS:

(7) Para cambiar el nombre del archivo 'suma.py' y sincronizarlo en GitHub, ejecuto:
	git mv suma.py operaciones.py
	git commit -m "Renombro suma.py a operaciones.py"
	git push

(8) Para cambiar el nombre del archivo 'test_suma.py' y sincronizarlo en GitHub, ejecuto:
	git mv test_suma.py test_operaciones.py
	git commit -m "Renombro test_suma.py a test_operaciones.py"
	git push

(11) Para comprobar las operaciones ejecuto:
	python3 operaciones.py

(14-15) Para comprobar los tests ejecuto:
	python3 test_operaciones.py

(15-16) Una vez modificados los archivos 'operaciones.py', 'test_operaciones.py' y 'ci.yml' (Actions) los sincronizo en GitHub ejecutando:
	git add git add .github/workflows/ci.yml
	git add operaciones.py
	git add test_operaciones.py
	git commit -m "Actualizo operaciones, pruebas y Actions"
	git push
