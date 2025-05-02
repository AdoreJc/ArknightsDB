# PauseEffectIf

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _checkOnPlay`

- `Boolean _checkAbnormalFlag`

- `AbnormalFlag _pauseWhenAbnormalFlag`

- `Boolean _checkAbnormalImmune`

- `AbnormalFlag _pauseWhenAbnormalImmune`

- `CheckType _checkAbnormalCombo`

- `AbnormalCombo _pauseWhenAbnormalCombo`

- `CheckType _checkUnitModeIndex`

- `CheckType _checkContainBuff`

- `String _pauseWhenContainBuffKey`

- `CheckType _checkCharacterSharedBlackboardKey`

- `CheckType _checkFaceToBack`

- `CheckType _checkFaceToRight`

- `Boolean _disableMeshRendererWhenPause`

- `Boolean _checkNotInAbnormalFlag`

- `AbnormalFlag _pauseWhenNotInAbnormalFlag`

- `CheckType _checkState`

- `State _pauseWhenCharState`


## Properties

- `Boolean checkAbnormalFlag`

- `Boolean checkAbnormalImmune`

- `Boolean checkAbnormalCombo`

- `Boolean checkContainBuff`

- `Boolean checkUnitModeIndex`

- `Boolean checkNotInAbnormalFlag`

- `Boolean checkCharacterSharedBlackboardKey`

- `Boolean checkState`


## Methods

- `Boolean get_checkAbnormalFlag()`

- `Boolean get_checkAbnormalImmune()`

- `Boolean get_checkAbnormalCombo()`

- `Boolean get_checkContainBuff()`

- `Boolean get_checkUnitModeIndex()`

- `Boolean get_checkNotInAbnormalFlag()`

- `Boolean get_checkCharacterSharedBlackboardKey()`

- `Boolean get_checkState()`

- `Void Update()`

- `Void _CheckPause()`

- `Boolean _CheckPauseIfFlag(CheckType, Boolean)`

- `Boolean _CheckContainBuffList()`

- `Void <>xLuaBaseProxy_Init(Effect)`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PauseEffectIf : Behaviour, IHotfixable
{
	private Boolean _checkOnPlay; // 0x20
	private Boolean _checkAbnormalFlag; // 0x21
	private AbnormalFlag _pauseWhenAbnormalFlag; // 0x24
	private List`1 _pauseWhenAbnormalFlags; // 0x28
	private Boolean _checkAbnormalImmune; // 0x30
	private AbnormalFlag _pauseWhenAbnormalImmune; // 0x34
	private CheckType _checkAbnormalCombo; // 0x38
	private AbnormalCombo _pauseWhenAbnormalCombo; // 0x3c
	private CheckType _checkUnitModeIndex; // 0x40
	private List`1 _pauseWhenModeIndexList; // 0x48
	private CheckType _checkContainBuff; // 0x50
	private String _pauseWhenContainBuffKey; // 0x58
	private List`1 _pauseWhenContainBuffKeyList; // 0x60
	private CheckType _checkCharacterSharedBlackboardKey; // 0x68
	private List`1 _characterSharedBlackboardKeyList; // 0x70
	private CheckType _checkFaceToBack; // 0x78
	private CheckType _checkFaceToRight; // 0x7c
	private Boolean _disableMeshRendererWhenPause; // 0x80
	private Boolean _checkNotInAbnormalFlag; // 0x81
	private AbnormalFlag _pauseWhenNotInAbnormalFlag; // 0x84
	private CheckType _checkState; // 0x88
	private State _pauseWhenCharState; // 0x8c
	private List`1 m_meshRenderers; // 0x90
	private static DelegateBridge __Hotfix0_get_checkAbnormalFlag; // 0x0
	private static DelegateBridge __Hotfix0_get_checkAbnormalImmune; // 0x8
	private static DelegateBridge __Hotfix0_get_checkAbnormalCombo; // 0x10
	private static DelegateBridge __Hotfix0_get_checkContainBuff; // 0x18
	private static DelegateBridge __Hotfix0_get_checkUnitModeIndex; // 0x20
	private static DelegateBridge __Hotfix0_get_checkNotInAbnormalFlag; // 0x28
	private static DelegateBridge __Hotfix0_get_checkCharacterSharedBlackboardKey; // 0x30
	private static DelegateBridge __Hotfix0_get_checkState; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_OnPlay; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x50
	private static DelegateBridge __Hotfix0__CheckPause; // 0x58
	private static DelegateBridge __Hotfix0_GetCheckResult; // 0x60
	private static DelegateBridge __Hotfix0__CheckPauseIfFlag; // 0x68
	private static DelegateBridge __Hotfix0__CheckContainBuffList; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Boolean checkAbnormalFlag { get; }
	public Boolean checkAbnormalImmune { get; }
	public Boolean checkAbnormalCombo { get; }
	public Boolean checkContainBuff { get; }
	public Boolean checkUnitModeIndex { get; }
	public Boolean checkNotInAbnormalFlag { get; }
	public Boolean checkCharacterSharedBlackboardKey { get; }
	public Boolean checkState { get; }

	// RVA: 0x20038e8 VA: 0x759461b8e8
	public Boolean get_checkAbnormalFlag() { }
	// RVA: 0x2003950 VA: 0x759461b950
	public Boolean get_checkAbnormalImmune() { }
	// RVA: 0x20039b8 VA: 0x759461b9b8
	public Boolean get_checkAbnormalCombo() { }
	// RVA: 0x2003a28 VA: 0x759461ba28
	public Boolean get_checkContainBuff() { }
	// RVA: 0x2003a98 VA: 0x759461ba98
	public Boolean get_checkUnitModeIndex() { }
	// RVA: 0x2003b08 VA: 0x759461bb08
	public Boolean get_checkNotInAbnormalFlag() { }
	// RVA: 0x2003b70 VA: 0x759461bb70
	public Boolean get_checkCharacterSharedBlackboardKey() { }
	// RVA: 0x2003be0 VA: 0x759461bbe0
	public Boolean get_checkState() { }
	// RVA: 0x2003c50 VA: 0x759461bc50
	public override Void Init(Effect effect) { }
	// RVA: 0x2003d60 VA: 0x759461bd60
	public override Void OnPlay() { }
	// RVA: 0x2003fc8 VA: 0x759461bfc8
	private Void Update() { }
	// RVA: 0x2003ddc VA: 0x759461bddc
	private Void _CheckPause() { }
	// RVA: 0x2004030 VA: 0x759461c030
	protected virtual Nullable`1 GetCheckResult() { }
	// RVA: 0x20049b4 VA: 0x759461c9b4
	private Boolean _CheckPauseIfFlag(CheckType checkType, Boolean flag) { }
	// RVA: 0x2004a54 VA: 0x759461ca54
	private Boolean _CheckContainBuffList() { }
	// RVA: 0x2004c70 VA: 0x759461cc70
	public Void .ctor() { }
	// RVA: 0x2004db0 VA: 0x759461cdb0
	private Void <>xLuaBaseProxy_Init(Effect P0) { }
	// RVA: 0x2004db4 VA: 0x759461cdb4
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```