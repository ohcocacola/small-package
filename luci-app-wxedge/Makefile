

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.1.4-20241002
PKG_RELEASE:=

LUCI_TITLE:=LuCI support for wxedge
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+lsblk +docker +dockerd +luci-lib-taskd

define Package/luci-app-wxedge/conffiles
/etc/config/wxedge
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
