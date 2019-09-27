include $(TOPDIR)/rules.mk

PKG_NAME:=ffhal-ssh-keys
PKG_VERSION:=1

PKG_BUILD_DIR:=$(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/ffhal-ssh-keys
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Adds a file with ssh keys used by Förderverein Freifunk Halle.
  DEPENDS:=
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/ffhal-ssh-keys/install
	$(CP) ./src/* $(1)/
endef

$(eval $(call BuildPackage,ffhal-ssh-keys))
