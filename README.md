name: workflow3
on: workflow_dispatch
jobs:
  print_hellow:
    runs-on: ubuntu-latest
    steps:
      - name: Print_hellow
        run: echo "Hello!"
        
  print_full_technical_info:
    runs-on: ubuntu-latest
    steps:
      - name: print_full_technical_info
        run: sudo lshw
         
  print_shorts_technical_info:
    runs-on: ubuntu-latest
    steps:
      - name: print_shorts_technical_info
        run: sudo lshw -short
