include $(TOPDIR)/rules.mk

PKG_NAME:=pyjwt
PKG_VERSION:=2.6.0
PKG_RELEASE:=1

PYPI_NAME:=PyJWT
PKG_HASH:=69285c7e31fc44f68a1feb309e948e0df53259d579295e6cfe2b1792329f05fd

#PKG_MAINTAINER:=Eneas U de Queiroz <cote2004-github@yahoo.com>
PKG_LICENSE:=MIT
PKG_LICENSE_FILES:=LICENSE

include $(INCLUDE_DIR)/../feeds/packages/lang/python/pypi.mk
include $(INCLUDE_DIR)/package.mk
include $(INCLUDE_DIR)/../feeds/packages/lang/python/python3-package.mk

define Package/python3-pyjwt
  SUBMENU:=Python
  SECTION:=lang
  CATEGORY:=Languages
  TITLE:=JSON Web Token implementation in Python
  URL:=http://github.com/jpadilla/pyjwt
  DEPENDS:=+python3
endef

define Package/python3-pyjwt/description
  A Python implementation of RFC 7519.
endef

$(eval $(call Py3Package,python3-pyjwt))
$(eval $(call BuildPackage,python3-pyjwt))
$(eval $(call BuildPackage,python3-pyjwt-src))
