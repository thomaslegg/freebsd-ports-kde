# Created by: Johannes Meixner <johannes@perceivon.net>
# $FreeBSD$

PORTNAME=	django-debug-toolbar
PORTVERSION=	1.6
CATEGORIES=	www python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	johannes@perceivon.net
COMMENT=	Configurable set of panels to display debug information

LICENSE=	BSD3CLAUSE

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}django18>=1.4.2:www/py-django18 \
		${PYTHON_PKGNAMEPREFIX}sqlparse>0:databases/py-sqlparse

USES=		python
USE_PYTHON=	autoplist distutils
NO_ARCH=	yes

.include <bsd.port.mk>
