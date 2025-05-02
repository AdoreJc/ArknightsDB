# SettingManager

**Namespace:** `Torappu.Setting`


## Fields

- `CommonSettingData m_commonSettingData`

- `PersonalSettingData m_personalSettingData`


## Methods

- `Object GetData(SettingType)`

- `Single GetVolumnValue()`

- `Void SetData(SettingType, Object, InstantFlag)`

- `Boolean GetFlag(SettingType)`

- `Void SetFlag(SettingType, Boolean, InstantFlag)`

- `Void ResetData()`

- `Boolean _ResetDataWithType(SettingType)`

- `Void LoadPersonal()`

- `Void LoadCommon()`

- `Void Save()`

- `Void _Init()`

- `Void _InitDataByDataGroupType(DataGroupType)`

- `Object <_Init>b__19_0()`

- `Void <_Init>b__19_1(Object)`

- `Object <_Init>b__19_2()`

- `Object <_Init>b__19_3()`

- `Void <_Init>b__19_4(Object)`

- `Object <_Init>b__19_5()`

- `Object <_Init>b__19_6()`

- `Void <_Init>b__19_7(Object)`

- `Object <_Init>b__19_8()`

- `Object <_Init>b__19_9()`

- `Void <_Init>b__19_10(Object)`

- `Object <_Init>b__19_11()`

- `Object <_Init>b__19_12()`

- `Void <_Init>b__19_13(Object)`

- `Object <_Init>b__19_14()`

- `Object <_Init>b__19_15()`

- `Void <_Init>b__19_16(Object)`

- `Object <_Init>b__19_17()`

- `Object <_Init>b__19_18()`

- `Void <_Init>b__19_19(Object)`

- `Object <_Init>b__19_20()`

- `Object <_Init>b__19_21()`

- `Void <_Init>b__19_22(Object)`

- `Object <_Init>b__19_23()`

- `Object <_Init>b__19_24()`

- `Void <_Init>b__19_25(Object)`

- `Object <_Init>b__19_26()`

- `Object <_Init>b__19_27()`

- `Void <_Init>b__19_28(Object)`

- `Object <_Init>b__19_29()`

- `Object <_Init>b__19_30()`

- `Void <_Init>b__19_31(Object)`

- `Object <_Init>b__19_32()`

- `Object <_Init>b__19_33()`

- `Void <_Init>b__19_34(Object)`

- `Object <_Init>b__19_35()`

- `Object <_Init>b__19_36()`

- `Void <_Init>b__19_37(Object)`

- `Object <_Init>b__19_38()`

- `Object <_Init>b__19_39()`

- `Void <_Init>b__19_40(Object)`

- `Object <_Init>b__19_41()`

- `Object <_Init>b__19_42()`

- `Void <_Init>b__19_43(Object)`

- `Object <_Init>b__19_44()`

- `Object <_Init>b__19_45()`

- `Void <_Init>b__19_46(Object)`

- `Object <_Init>b__19_47()`

- `Object <_Init>b__19_48()`

- `Void <_Init>b__19_49(Object)`

- `Object <_Init>b__19_50()`

- `Object <_Init>b__19_51()`

- `Void <_Init>b__19_52(Object)`

- `Object <_Init>b__19_53()`

- `Object <_Init>b__19_57()`

- `Void <_Init>b__19_58(Object)`

- `Object <_Init>b__19_59()`

- `Object <_Init>b__19_60()`

- `Void <_Init>b__19_61(Object)`

- `Object <_Init>b__19_62()`

- `Object <_Init>b__19_66()`

- `Void <_Init>b__19_67(Object)`

- `Object <_Init>b__19_68()`

- `Object <_Init>b__19_69()`

- `Void <_Init>b__19_70(Object)`

- `Object <_Init>b__19_71()`

- `Object <_Init>b__19_72()`

- `Void <_Init>b__19_73(Object)`

- `Object <_Init>b__19_74()`

- `Object <_Init>b__19_75()`

- `Void <_Init>b__19_76(Object)`

- `Object <_Init>b__19_77()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Setting
public class SettingManager : Singleton`1
{
	private CommonSettingData m_commonSettingData; // 0x10
	private PersonalSettingData m_personalSettingData; // 0x18
	public Action`1 instantSettingAction; // 0x20
	private Dictionary`2 m_bindingDic; // 0x28
	private static DelegateBridge __Hotfix0_GetData; // 0x0
	private static DelegateBridge __Hotfix0_GetVolumnValue; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_GetFlag; // 0x18
	private static DelegateBridge __Hotfix0_SetFlag; // 0x20
	private static DelegateBridge __Hotfix0_ResetData; // 0x28
	private static DelegateBridge __Hotfix0__ResetDataWithType; // 0x30
	private static DelegateBridge __Hotfix0_LoadPersonal; // 0x38
	private static DelegateBridge __Hotfix0_LoadCommon; // 0x40
	private static DelegateBridge __Hotfix0_Save; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50
	private static DelegateBridge __Hotfix0__Init; // 0x58
	private static DelegateBridge __Hotfix0__InitDataByDataGroupType; // 0x60


	// RVA: 0x3e35504 VA: 0x759644d504
	public Object GetData(SettingType type) { }
	// RVA: 0x3e355d8 VA: 0x759644d5d8
	public Single GetVolumnValue() { }
	// RVA: 0x3e356d8 VA: 0x759644d6d8
	public Void SetData(SettingType type, Object value, InstantFlag instant) { }
	// RVA: 0x3e3590c VA: 0x759644d90c
	public Boolean GetFlag(SettingType type) { }
	// RVA: 0x3e35aa8 VA: 0x759644daa8
	public Void SetFlag(SettingType type, Boolean value, InstantFlag instant) { }
	// RVA: 0x3e35c50 VA: 0x759644dc50
	public Void ResetData() { }
	// RVA: 0x3e365d4 VA: 0x759644e5d4
	private Boolean _ResetDataWithType(SettingType type) { }
	// RVA: 0x3e366f8 VA: 0x759644e6f8
	public Void LoadPersonal() { }
	// RVA: 0x3e36b1c VA: 0x759644eb1c
	public Void LoadCommon() { }
	// RVA: 0x3e357e8 VA: 0x759644d7e8
	public Void Save() { }
	// RVA: 0x3e36c88 VA: 0x759644ec88
	protected Void .ctor() { }
	// RVA: 0x3e36e18 VA: 0x759644ee18
	private Void _Init() { }
	// RVA: 0x3e368bc VA: 0x759644e8bc
	private Void _InitDataByDataGroupType(DataGroupType dataGroupType) { }
	// RVA: 0x3e38cc0 VA: 0x7596450cc0
	private Object <_Init>b__19_0() { }
	// RVA: 0x3e38d20 VA: 0x7596450d20
	private Void <_Init>b__19_1(Object value) { }
	// RVA: 0x3e38da0 VA: 0x7596450da0
	private Object <_Init>b__19_2() { }
	// RVA: 0x3e38e00 VA: 0x7596450e00
	private Object <_Init>b__19_3() { }
	// RVA: 0x3e38e60 VA: 0x7596450e60
	private Void <_Init>b__19_4(Object value) { }
	// RVA: 0x3e38ee0 VA: 0x7596450ee0
	private Object <_Init>b__19_5() { }
	// RVA: 0x3e38f40 VA: 0x7596450f40
	private Object <_Init>b__19_6() { }
	// RVA: 0x3e38fa0 VA: 0x7596450fa0
	private Void <_Init>b__19_7(Object value) { }
	// RVA: 0x3e39020 VA: 0x7596451020
	private Object <_Init>b__19_8() { }
	// RVA: 0x3e39080 VA: 0x7596451080
	private Object <_Init>b__19_9() { }
	// RVA: 0x3e390e0 VA: 0x75964510e0
	private Void <_Init>b__19_10(Object value) { }
	// RVA: 0x3e39160 VA: 0x7596451160
	private Object <_Init>b__19_11() { }
	// RVA: 0x3e391c4 VA: 0x75964511c4
	private Object <_Init>b__19_12() { }
	// RVA: 0x3e39224 VA: 0x7596451224
	private Void <_Init>b__19_13(Object value) { }
	// RVA: 0x3e392a4 VA: 0x75964512a4
	private Object <_Init>b__19_14() { }
	// RVA: 0x3e39308 VA: 0x7596451308
	private Object <_Init>b__19_15() { }
	// RVA: 0x3e39368 VA: 0x7596451368
	private Void <_Init>b__19_16(Object value) { }
	// RVA: 0x3e393e8 VA: 0x75964513e8
	private Object <_Init>b__19_17() { }
	// RVA: 0x3e3944c VA: 0x759645144c
	private Object <_Init>b__19_18() { }
	// RVA: 0x3e394ac VA: 0x75964514ac
	private Void <_Init>b__19_19(Object value) { }
	// RVA: 0x3e3952c VA: 0x759645152c
	private Object <_Init>b__19_20() { }
	// RVA: 0x3e39590 VA: 0x7596451590
	private Object <_Init>b__19_21() { }
	// RVA: 0x3e395f0 VA: 0x75964515f0
	private Void <_Init>b__19_22(Object value) { }
	// RVA: 0x3e39670 VA: 0x7596451670
	private Object <_Init>b__19_23() { }
	// RVA: 0x3e396d4 VA: 0x75964516d4
	private Object <_Init>b__19_24() { }
	// RVA: 0x3e39734 VA: 0x7596451734
	private Void <_Init>b__19_25(Object value) { }
	// RVA: 0x3e397b4 VA: 0x75964517b4
	private Object <_Init>b__19_26() { }
	// RVA: 0x3e39818 VA: 0x7596451818
	private Object <_Init>b__19_27() { }
	// RVA: 0x3e39878 VA: 0x7596451878
	private Void <_Init>b__19_28(Object value) { }
	// RVA: 0x3e398f8 VA: 0x75964518f8
	private Object <_Init>b__19_29() { }
	// RVA: 0x3e3995c VA: 0x759645195c
	private Object <_Init>b__19_30() { }
	// RVA: 0x3e399bc VA: 0x75964519bc
	private Void <_Init>b__19_31(Object value) { }
	// RVA: 0x3e39a3c VA: 0x7596451a3c
	private Object <_Init>b__19_32() { }
	// RVA: 0x3e39a9c VA: 0x7596451a9c
	private Object <_Init>b__19_33() { }
	// RVA: 0x3e39afc VA: 0x7596451afc
	private Void <_Init>b__19_34(Object value) { }
	// RVA: 0x3e39b7c VA: 0x7596451b7c
	private Object <_Init>b__19_35() { }
	// RVA: 0x3e39be0 VA: 0x7596451be0
	private Object <_Init>b__19_36() { }
	// RVA: 0x3e39c40 VA: 0x7596451c40
	private Void <_Init>b__19_37(Object value) { }
	// RVA: 0x3e39cc0 VA: 0x7596451cc0
	private Object <_Init>b__19_38() { }
	// RVA: 0x3e39d24 VA: 0x7596451d24
	private Object <_Init>b__19_39() { }
	// RVA: 0x3e39d84 VA: 0x7596451d84
	private Void <_Init>b__19_40(Object value) { }
	// RVA: 0x3e39e04 VA: 0x7596451e04
	private Object <_Init>b__19_41() { }
	// RVA: 0x3e39e68 VA: 0x7596451e68
	private Object <_Init>b__19_42() { }
	// RVA: 0x3e39ec8 VA: 0x7596451ec8
	private Void <_Init>b__19_43(Object value) { }
	// RVA: 0x3e39f48 VA: 0x7596451f48
	private Object <_Init>b__19_44() { }
	// RVA: 0x3e39fac VA: 0x7596451fac
	private Object <_Init>b__19_45() { }
	// RVA: 0x3e3a00c VA: 0x759645200c
	private Void <_Init>b__19_46(Object value) { }
	// RVA: 0x3e3a08c VA: 0x759645208c
	private Object <_Init>b__19_47() { }
	// RVA: 0x3e3a0f0 VA: 0x75964520f0
	private Object <_Init>b__19_48() { }
	// RVA: 0x3e3a150 VA: 0x7596452150
	private Void <_Init>b__19_49(Object value) { }
	// RVA: 0x3e3a1d0 VA: 0x75964521d0
	private Object <_Init>b__19_50() { }
	// RVA: 0x3e3a234 VA: 0x7596452234
	private Object <_Init>b__19_51() { }
	// RVA: 0x3e3a294 VA: 0x7596452294
	private Void <_Init>b__19_52(Object value) { }
	// RVA: 0x3e3a314 VA: 0x7596452314
	private Object <_Init>b__19_53() { }
	// RVA: 0x3e3a378 VA: 0x7596452378
	private Object <_Init>b__19_57() { }
	// RVA: 0x3e3a3d8 VA: 0x75964523d8
	private Void <_Init>b__19_58(Object value) { }
	// RVA: 0x3e3a458 VA: 0x7596452458
	private Object <_Init>b__19_59() { }
	// RVA: 0x3e3a4b8 VA: 0x75964524b8
	private Object <_Init>b__19_60() { }
	// RVA: 0x3e3a518 VA: 0x7596452518
	private Void <_Init>b__19_61(Object value) { }
	// RVA: 0x3e3a598 VA: 0x7596452598
	private Object <_Init>b__19_62() { }
	// RVA: 0x3e3a5f8 VA: 0x75964525f8
	private Object <_Init>b__19_66() { }
	// RVA: 0x3e3a658 VA: 0x7596452658
	private Void <_Init>b__19_67(Object value) { }
	// RVA: 0x3e3a6d8 VA: 0x75964526d8
	private Object <_Init>b__19_68() { }
	// RVA: 0x3e3a73c VA: 0x759645273c
	private Object <_Init>b__19_69() { }
	// RVA: 0x3e3a79c VA: 0x759645279c
	private Void <_Init>b__19_70(Object value) { }
	// RVA: 0x3e3a81c VA: 0x759645281c
	private Object <_Init>b__19_71() { }
	// RVA: 0x3e3a880 VA: 0x7596452880
	private Object <_Init>b__19_72() { }
	// RVA: 0x3e3a8e0 VA: 0x75964528e0
	private Void <_Init>b__19_73(Object value) { }
	// RVA: 0x3e3a960 VA: 0x7596452960
	private Object <_Init>b__19_74() { }
	// RVA: 0x3e3a9c0 VA: 0x75964529c0
	private Object <_Init>b__19_75() { }
	// RVA: 0x3e3aa20 VA: 0x7596452a20
	private Void <_Init>b__19_76(Object value) { }
	// RVA: 0x3e3aaa0 VA: 0x7596452aa0
	private Object <_Init>b__19_77() { }
}
```