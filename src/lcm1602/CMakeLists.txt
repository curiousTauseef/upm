upm_mixed_module_init (NAME lcm1602
    DESCRIPTION "LCD Display Driver for the LCM1602 Controller for HD44780-based Displays"
    C_HDR lcm1602.h
    C_SRC lcm1602.c
    CPP_HDR lcm1602.hxx
    CPP_SRC lcm1602.cxx
#    FTI_SRC lcm1602_fti.c
    CPP_WRAPS_C
    REQUIRES mraa)
