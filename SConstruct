# -*- python -*-
import os

env = Environment(ENV=os.environ)

dviOutput = env.DVI(
    target = 'hello-world.dvi', 
    source = ['hello-world.tex'],
)
pdfOutput = env.PDF(
    target = 'hello-world.pdf',
    source = ['hello-world.dvi'],
)
Depends(pdfOutput, dviOutput)

