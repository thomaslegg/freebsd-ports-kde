# Created by: Michael Lyngb�l <lyngbol@wheel.dk>
# $FreeBSD$

PORTNAME=	scli
PORTVERSION=	0.3.1
PORTREVISION=	3
CATEGORIES=	net-mgmt
MASTER_SITES=	ftp://ftp.ibr.cs.tu-bs.de/local/${PORTNAME}/ \
		http://matt.peterson.org/FreeBSD/ports/

MAINTAINER=	lyngbol@wheel.dk
COMMENT=	A collection of SNMP command line management tools

LIB_DEPENDS=	libgsnmp.so:net-mgmt/gsnmp

GNU_CONFIGURE=	yes
USES=		gmake ncurses pkgconfig readline
USE_GNOME=	libxml2

INFO=		scli
PLIST_FILES=	bin/scli man/man1/scli.1.gz

.include <bsd.port.mk>
