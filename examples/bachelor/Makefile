# name of your application
APPLICATION = bachelor

# If no BOARD is found in the environment, use this default:
BOARD ?= nucleo-l552ze-q

# This has to be the absolute path to the RIOT base directory:
RIOTBASE ?= $(CURDIR)/../..

# Comment this out to disable code in RIOT that does safety checking
# which is not needed in a production environment but helps in the
# development process:
DEVELHELP ?= 1

# Change this to 0 show compiler invocation lines by default:
QUIET ?= 1

FEATURES_REQUIRED += riotboot
FEATURES_OPTIONAL += periph_timer

USEMODULE += ztimer_usec
USEMODULE += cortexm_svc

CFLAGS += -mcmse -O0

include $(RIOTBASE)/Makefile.include
