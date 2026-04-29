V=		2.23.1
COMMENT=	command line parser for c programs
DISTNAME=	gengetopt-${V}
CATEGORIES=	devel

HOMEPAGE=	http://www.gnu.org/software/gengetopt/

# GPLv3+
PERMIT_PACKAGE=	Yes

WANTLIB += c m ${COMPILER_LIBCXX}

COMPILER=	base-clang ports-gcc base-gcc

SITES=		${SITE_GNU:=gengetopt/}

CONFIGURE_STYLE=	gnu
USE_GMAKE=	Yes
MODGNU_CONFIG_GUESS_DIRS=	${WRKSRC} ${WRKSRC}/build-aux
.include <bsd.port.mk>
