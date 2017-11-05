# Created by: ganbold@
# $FreeBSD$

PORTNAME=	grpcio-tools
PORTVERSION=	1.7.0
CATEGORIES=	devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	vanilla@FreeBSD.org
COMMENT=	HTTP/2-based RPC framework tools

LICENSE=	BSD3CLAUSE

RUN_DEPENDS?=	${PYTHON_PKGNAMEPREFIX}grpcio>1:devel/py-grpcio

USES?=		localbase:ldflags python
USE_PYTHON=	distutils
CFLAGS+=	-DHAVE_PTHREAD=1 -DGOOGLE_PROTOBUF_NO_RTTI
#LDFLAGS+=	-lcares

#post-install:
#	${STRIP_CMD} ${STAGEDIR}${PYTHONPREFIX_SITELIBDIR}/grpc/_cython/cygrpc.so

.include <bsd.port.mk>
