#
# Variables
#
GOX_FLAGS=-arch="amd64 386 arm ppc64 ppc64le"
ES_BEATS?=../../

#
# Includes
#
include $(ES_BEATS)/dev-tools/make/xpack.mk

.PHONY: test-gcp-functions
test-gcp-functions: mage
	mage testGCPFunctions
