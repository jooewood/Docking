# Python call smina to do docking

this program can use multiple CPU.

-r: target PDB/PDBQT file.  
-f: crystal ligand PDB/PDBQT file.  
-l: A SDF/SMI/CSV file includes compounds for dock.  
-o: Output folder
```
./docking.py -r /home/zdx/target.pdb -f /home/zdx/crystal_ligand.pdbqt -l /home/zdx/actives_final.ism -o /home/zdx/XXX
```
