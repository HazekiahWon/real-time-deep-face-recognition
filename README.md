# facetype recognition
## usage
### installation
1. install anaconda  
2. open `conda prompt`, type:  
`git clone https://github.com/HazekiahWon/facetype_rec.git`  
`cd facetype_rec`
3. in `conda prompt`, type:  
`conda install --file requirements.txt`
4. create a folder `ftdata` and put your images there.
### testing
1. By default :
`python realtime_facenet_git.py --rel_path ftdata\polygon`
2. In order to show every image :
`python realtime_facenet_git.py --show_flag 1 --rel_path ftdata\polygon` 
3. if you set `show_flag` to `1`:  
type `q` to quit, and any other key to continue.
### Catching with the code
go to your installation directory, e.g. `cd facetype_rec`  
`git pull`


