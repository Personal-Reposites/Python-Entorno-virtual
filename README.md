#  Python Virtual Env Steps

## 1- Running Programm

### Creating the Env(Any Name)
```
python -m venv myEntorno
```

###  Activating the <EnvNamePicked>
```
myEntorno\Scripts\activate  # o source myEntorno/bin/activate
```

### Install the requirements
```
pip install -r requirements.txt
```

### Run the Pyhon Script (main.py)
```
python main.py
```



# -------- Steps  to Create Any Virtual Env --------------

## Step 1: Create Proyect 

### Create new File
```
	mkdir holaProyectFolder
```

###  Go to The File Created
```
cd holaProyec
```

## Step 2:  Pyhton virtual Env

### create virual env
```
python -m venv myEntorno
```

###  Activate this env
```
myEntorno\Scripts\activate
```

## Step 3:  install pip Lib 

### Install lib will use in the code Ex: colorama en myEntorno
```
install colorama 
```

## Step 4:  Create the Pyhon Scripts

### main.py
```	
	from colorama import init, Fore
	init()  # Necesario en Windows
	print(Fore.GREEN + "Hola Mundo en verde!" + Fore.RESET)
```

## Step 5:  Run the Pyhon Scripts

### Run main.py
```	
python main.py

```

## Step 6:  Save & installing the pip lib dependences

### Catch all the pip lib in the Current Env t
```	
pip freeze > requirements.txt

```

### installing all requirements
```	
pip install -r requirements.txt

```

## Step 7:  deactivate the  entorno virtual

### deactivate in CLI
```	
deactivate

```


## Structure
```
holaProyectFolder/
│── main.py
│── requirements.txt
│── .gitignore
│── README.md
│── myEntorno/   ← carpeta del entorno virtual (NO se sube a GitHub)

```	