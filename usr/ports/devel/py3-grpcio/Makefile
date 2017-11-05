# Created by: Ganbold Tsagaankhuu <ganbold@FreeBSD.org>
# $FreeBSD$

MASTERDIR=	${.CURDIR}/../py-grpcio
PLIST=          ${.CURDIR}/pkg-plist

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}six>1:devel/py-six \
		${PYTHON_PKGNAMEPREFIX}protobuf>=3:devel/py-protobuf

USES=		localbase:ldflags python:3.3+

.include "${MASTERDIR}/Makefile"
