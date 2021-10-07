#
# Makefile
#

# set the executable name
EXEC=rpn

all: test 

test: 
	baygon -v -t t.yaml ./$(EXEC)

.PHONY:	clean all test
.DEFAULT: test 
