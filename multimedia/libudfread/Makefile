COMMENT=	library for reading UDF from raw devices and image files

DISTNAME=	libudfread-1.1.2
CATEGORIES=	multimedia devel
SITES=		https://download.videolan.org/videolan/libudfread/
EXTRACT_SUFX=	.tar.bz2

SHARED_LIBS=	udfread	0.0

HOMEPAGE=	https://code.videolan.org/videolan/libudfread/

# LGPLv2.1
PERMIT_PACKAGE=	Yes

CONFIGURE_STYLE=gnu
MODGNU_CONFIG_GUESS_DIRS=${WRKSRC} ${WRKSRC}/build-aux
NO_TEST=	Yes

.include <bsd.port.mk>
