TWEAK_NAME = DiaryiPhone DiaryiPad

DiaryiPhone_FILES = iPhone/Diary.x DRYLocalization.m
DiaryiPhone_CFLAGS = -fobjc-arc -DTHEOS_LEAN_AND_MEAN
DiaryiPhone_FRAMEWORKS = UIKit CoreText CoreTelephony EventKit
DiaryiPhone_PRIVATE_FRAMEWORKS = MediaRemote
DiaryiPhone_EXTRA_FRAMEWORKS = Cephei
DiaryiPhone_LIBRARIES = gcuniversal pddokdo kitten

DiaryiPad_FILES = iPad/Diary.x DRYLocalization.m
DiaryiPad_CFLAGS = -fobjc-arc -DTHEOS_LEAN_AND_MEAN
DiaryiPad_FRAMEWORKS = UIKit CoreText CoreTelephony EventKit
DiaryiPad_PRIVATE_FRAMEWORKS = MediaRemote
DiaryiPad_EXTRA_FRAMEWORKS = Cephei
DiaryiPad_LIBRARIES = gcuniversal pddokdo kitten

include $(THEOS)/makefiles/common.mk
include $(THEOS_MAKE_PATH)/tweak.mk
