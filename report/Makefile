

# src = n4631
src = pre-toronto

all: pdf html

pdf: ${src}.md
	pandoc ${src}.md -o ${src}.pdf

html: ${src}.md
	pandoc ${src}.md -o ${src}.html


clean:
	rm -f ${src}.pdf ${src}.html

