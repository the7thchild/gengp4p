# gengp4p
A program to generate PSVita Publishing Tool GP4P file from a directroy

Usage: gengp4 <directory name> <output path>
Precaution: If your folder contains:
1. sce_sys\about
2. sce_sys\clearsign
3. sce_sys\keystone
The resulting gp4p file will be rejected by Publishing tool, the program assume a blank spacer inside debug pkg for SCEI's future operation.
