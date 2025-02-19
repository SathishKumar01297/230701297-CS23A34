def main():
  print("Choose an interface:")
  print("1. Graphical User Interface (GUI)")
  print("2. Command Line Interface (CLI)")
  choice = input("Enter your choice (1 or 2): ")

  if choice == '1':
      from gui import start_gui
      start_gui()
  elif choice == '2':
      from cli import start_cli
      start_cli()
  else:
      print("Invalid choice. Exiting... bye bye")

if __name__ == "__main__":
  main()