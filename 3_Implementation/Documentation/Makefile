DOXY_FILE = Wiper Control System
BULID_FILE = html


FixPath = $(subst /, \, $1)

Doc :
          doxygen ./$(DOXY_FILE)
          
Clean:
      rm -rf $(call FixPath,$(BUILD_FILE)/*)
      
