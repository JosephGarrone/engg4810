################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./adc.obj" \
"./button.obj" \
"./customstdio.obj" \
"./input.obj" \
"./print.obj" \
"./relay.obj" \
"./screen.obj" \
"./spi.obj" \
"./startup.obj" \
"./startup_ccs.obj" \
"./system.obj" \
"./utils.obj" \
"./drivers/ads124x.obj" \
"./drivers/buttons.obj" \
"./drivers/fat_fs_sd.obj" \
"./drivers/rgb.obj" \
"./handlers/cont.obj" \
"./handlers/current.obj" \
"./handlers/general.obj" \
"./handlers/logic.obj" \
"./handlers/resistance.obj" \
"./handlers/voltage.obj" \
"./third_party/FreeRTOS/Source/list.obj" \
"./third_party/FreeRTOS/Source/queue.obj" \
"./third_party/FreeRTOS/Source/tasks.obj" \
"./third_party/FreeRTOS/Source/portable/CCS/ARM_CM4F/port.obj" \
"./third_party/FreeRTOS/Source/portable/CCS/ARM_CM4F/portasm.obj" \
"./third_party/FreeRTOS/Source/portable/MemMang/heap_2.obj" \
"./third_party/TivaLCD/display.obj" \
"./utils/ustdlib.obj" \
"../startup_ccs.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-l"C:/ti/TivaWare_C_Series-2.1.4.178/driverlib/ccs/Debug/driverlib.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include drivers/subdir_vars.mk
-include handlers/subdir_vars.mk
-include third_party/FreeRTOS/Source/subdir_vars.mk
-include third_party/FreeRTOS/Source/portable/CCS/ARM_CM4F/subdir_vars.mk
-include third_party/FreeRTOS/Source/portable/MemMang/subdir_vars.mk
-include third_party/TivaLCD/subdir_vars.mk
-include utils/subdir_vars.mk
-include subdir_rules.mk
-include drivers/subdir_rules.mk
-include handlers/subdir_rules.mk
-include third_party/FreeRTOS/Source/subdir_rules.mk
-include third_party/FreeRTOS/Source/portable/CCS/ARM_CM4F/subdir_rules.mk
-include third_party/FreeRTOS/Source/portable/MemMang/subdir_rules.mk
-include third_party/TivaLCD/subdir_rules.mk
-include utils/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
Firmware.out \

EXE_OUTPUTS__QUOTED += \
"Firmware.out" \

BIN_OUTPUTS += \
Firmware.bin \

BIN_OUTPUTS__QUOTED += \
"Firmware.bin" \


# All Target
all: Firmware.out

# Tool invocations
Firmware.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armcl" -mv7M4 --code_state=16 --float_support=FPv4SPD16 --abi=eabi -me -Ooff --advice:power=all -g --c99 --gcc --define=ccs="ccs" --define=PART_TM4C123GH6PM --define=TARGET_IS_TM4C123_RB1 --diag_wrap=off --diag_warning=225 --display_error_number --gen_func_subsections=on --printf_support=full --ual -z -m"freertos_demo_ccs.map" --heap_size=0 --stack_size=512 -i"C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/lib" -i"C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/include" --reread_libs --display_error_number --diag_wrap=off --warn_sections --xml_link_info="Firmware_linkInfo.xml" --rom_model -o "Firmware.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

Firmware.bin: $(EXE_OUTPUTS)
	@echo 'Invoking: ARM Hex Utility'
	"C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armhex"  -o "Firmware.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "adc.obj" "button.obj" "customstdio.obj" "input.obj" "print.obj" "relay.obj" "screen.obj" "spi.obj" "startup.obj" "startup_ccs.obj" "system.obj" "utils.obj" "drivers\ads124x.obj" "drivers\buttons.obj" "drivers\fat_fs_sd.obj" "drivers\rgb.obj" "handlers\cont.obj" "handlers\current.obj" "handlers\general.obj" "handlers\logic.obj" "handlers\resistance.obj" "handlers\voltage.obj" "third_party\FreeRTOS\Source\list.obj" "third_party\FreeRTOS\Source\queue.obj" "third_party\FreeRTOS\Source\tasks.obj" "third_party\FreeRTOS\Source\portable\CCS\ARM_CM4F\port.obj" "third_party\FreeRTOS\Source\portable\CCS\ARM_CM4F\portasm.obj" "third_party\FreeRTOS\Source\portable\MemMang\heap_2.obj" "third_party\TivaLCD\display.obj" "utils\ustdlib.obj" 
	-$(RM) "adc.d" "button.d" "customstdio.d" "input.d" "print.d" "relay.d" "screen.d" "spi.d" "startup.d" "startup_ccs.d" "system.d" "utils.d" "drivers\ads124x.d" "drivers\buttons.d" "drivers\fat_fs_sd.d" "drivers\rgb.d" "handlers\cont.d" "handlers\current.d" "handlers\general.d" "handlers\logic.d" "handlers\resistance.d" "handlers\voltage.d" "third_party\FreeRTOS\Source\list.d" "third_party\FreeRTOS\Source\queue.d" "third_party\FreeRTOS\Source\tasks.d" "third_party\FreeRTOS\Source\portable\CCS\ARM_CM4F\port.d" "third_party\FreeRTOS\Source\portable\MemMang\heap_2.d" "third_party\TivaLCD\display.d" "utils\ustdlib.d" 
	-$(RM) "third_party\FreeRTOS\Source\portable\CCS\ARM_CM4F\portasm.d" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"C:/ti/ccsv7/utils/tiobj2bin/tiobj2bin" "Firmware.out" "Firmware.bin" "C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armofd" "C:/ti/ccsv7/tools/compiler/ti-cgt-arm_16.9.1.LTS/bin/armhex" "C:/ti/ccsv7/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

