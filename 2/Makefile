
# Help
.PHONY: help
help:
	@echo lsl 
	@echo "RefOS - Reference multi-server OS on seL4."
	@echo ""
	@echo " make help            - Show this help test."
	@echo " make menuconfig      - Select build configuration via menus."
	@echo " make <defconfig>     - Apply one of the default configurations. See"
	@echo "                        below for valid configurations."
	@echo " make silentoldconfig - Update configuration with the defaults of any"
	@echo "                        newly introduced settings."
	@echo " make                 - Build everything with the current configuration."
	@echo " make generate-rpc    - Generate RPC stubs from XML specs."
	@echo " make clean-rpc       - Delete generated RPC stubs."
	@echo " make refos           - Build RefOS without re-generating RPC stub code."
	@echo " make cscope          - Build cscope.out index file using cscope."
	@echo " make docs            - Build docs/html/ Doxygen code documentation."
	@echo " make design          - Build protocol design document."
	@echo ""
	@echo "Valid default configurations are:"
	@ls -1 configs # | sed -e 's/ \(.*\) / \t \1 /g'  #'s/ / /g'
	@echo ""
