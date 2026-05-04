COMMENT=	C implementation of the Frame Streams protocol

DISTNAME=	fstrm-0.6.1
CATEGORIES=	net devel

SHARED_LIBS +=  fstrm                0.0

HOMEPAGE=	https://github.com/farsightsec/fstrm

MAINTAINER=	Otto Moerbeek <otto@drijf.net>

# MIT
PERMIT_PACKAGE=	Yes

WANTLIB += c event_core event_extra pthread

SITES=		https://dl.farsightsecurity.com/dist/fstrm/

LIB_DEPENDS=	devel/libevent2

CONFIGURE_STYLE= gnu
MODGNU_CONFIG_GUESS_DIRS=${WRKSRC} ${WRKSRC}/build-auxUSE_GMAKE=	Yes

.include <bsd.port.mk>
