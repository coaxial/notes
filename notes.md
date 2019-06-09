# convert image to pdf
`ls -1 image-*.jpg | xargs -L1 -I {} img2pdf {} -o {}.pdf`

# combine pdf documents into one
`pdftk document.pdf image-*.pdf cat output combined.pdf`
