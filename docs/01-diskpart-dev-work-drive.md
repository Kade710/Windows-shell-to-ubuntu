# DiskPart: DEV_WORK Drive Prep (Windows PowerShell Admin)

>WARNING: "clean" wipes the selected disk. confirm disk number carefully (check, double check, TRIPLE CHECK!!!!)

## Steps

Open *Windows PowerShell (Admin)* and run:
```powershell
diskpart
list disk
select disk
clean
create partion primary
format fs=ntfs quick label=DEV_WORK
assign letter=W
exit
