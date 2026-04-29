COMMENT =	terminal screen handling and optimisation

DISTNAME =	Curses-1.46
FIX_EXTRACT_PERMISSIONS = Yes

CATEGORIES =	devel

# Perl
PERMIT_PACKAGE =	Yes

CPAN_AUTHOR =		GIRAFFED

WANTLIB =		c curses form menu panel perl

MODULES =		cpan

MAKE_FLAGS =		PASTHRU_DEFINE='-idirafter $${PERL_INC}'

CONFIGURE_ARGS =	PANELS MENUS FORMS

post-extract:
	cp ${WRKSRC}/hints/c-openbsd.h ${WRKSRC}/hints/c-iabsd.h

.include <bsd.port.mk>
