#
# Copyright (C) 2015 OpenWrt-dist
#
# This is free software, licensed under the GNU General Public License v3.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=ipv6settings
PKG_VERSION:=1.0
PKG_RELEASE:=1

PKG_LICENSE:=GPLv3
PKG_LICENSE_FILES:=LICENSE
PKG_MAINTAINER:=Carbon

PKG_BUILD_DIR:=$(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/ipv6settings
	SECTION:=ipv6
	TITLE:=IPv6 Settings Helper
	PKGARCH:=all
	DEPENDS:=+luci-proto-ipv6 +wget +ip6tables +libip6tc +kmod-ipt-nat6 +odhcpd-ipv6only +odhcp6c +6in4 \
			 +vim-runtime +vim +whereis +which +lrzsz +lscpu +bash \
			 +@LUCI_LANG_zh-cn +@LUCI_LANG_zh_Hans +@LUCI_LANG_en
endef

define Package/ipv6settings/description
	IPv6 Settings Helper
endef

define Build/Prepare
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/ipv6settings/postinst
endef

define Package/ipv6settings/install
endef


$(eval $(call BuildPackage,ipv6settings))
