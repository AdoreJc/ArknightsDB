# HandBookInfoStagePage

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `UIAnimationLocation _enterAnim`

- `Tween m_enterAnim`

- `HandBookJumpParam <jumpParam>k__BackingField`

- `HandBookInfoStageProperty m_stageProperty`


## Properties

- `HandBookJumpParam jumpParam`

- `HandBookInfoStageProperty property`

- `Boolean isPlaying`


## Methods

- `HandBookJumpParam get_jumpParam()`

- `Void set_jumpParam(HandBookJumpParam)`

- `HandBookInfoStageProperty get_property()`

- `Boolean get_isPlaying()`

- `Void _PlayEnterAnim()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStagePage : StateEnginePage
{
	private UIAnimationLocation _enterAnim; // 0xe8
	private Tween m_enterAnim; // 0xf8
	private HandBookJumpParam <jumpParam>k__BackingField; // 0x100
	private HandBookInfoStageProperty m_stageProperty; // 0x108
	private static DelegateBridge __Hotfix0_get_jumpParam; // 0x0
	private static DelegateBridge __Hotfix0_set_jumpParam; // 0x8
	private static DelegateBridge __Hotfix0_get_property; // 0x10
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x28
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public HandBookJumpParam jumpParam { get; set; }
	public HandBookInfoStageProperty property { get; }
	public Boolean isPlaying { get; }

	// RVA: 0x2e99744 VA: 0x75954b1744
	public HandBookJumpParam get_jumpParam() { }
	// RVA: 0x2e997ac VA: 0x75954b17ac
	public Void set_jumpParam(HandBookJumpParam value) { }
	// RVA: 0x2e99830 VA: 0x75954b1830
	public HandBookInfoStageProperty get_property() { }
	// RVA: 0x2e99898 VA: 0x75954b1898
	public Boolean get_isPlaying() { }
	// RVA: 0x2e99914 VA: 0x75954b1914
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2e99d64 VA: 0x75954b1d64
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2e99e4c VA: 0x75954b1e4c
	private Void _PlayEnterAnim() { }
	// RVA: 0x2e99fa4 VA: 0x75954b1fa4
	public Void .ctor() { }
	// RVA: 0x2e9a054 VA: 0x75954b2054
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2e9a05c VA: 0x75954b205c
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
}
```