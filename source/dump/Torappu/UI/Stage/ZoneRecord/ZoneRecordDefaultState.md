# ZoneRecordDefaultState

**Namespace:** `Torappu.UI.Stage.ZoneRecord`


## Fields

- `Boolean m_isInited`

- `RectTransform m_controllerContainer`

- `String m_cachedZoneId`

- `ZoneRecordController m_controller`


## Methods

- `Void _InitIfNot()`

- `Void _InitDecodeView(String)`

- `Void _CloseZoneRecord()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord
public class ZoneRecordDefaultState : State
{
	private Boolean m_isInited; // 0x50
	private RectTransform m_controllerContainer; // 0x58
	private String m_cachedZoneId; // 0x60
	private ZoneRecordController m_controller; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__InitDecodeView; // 0x20
	private static DelegateBridge __Hotfix0__CloseZoneRecord; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2fcbf98 VA: 0x75955e3f98
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2fcbffc VA: 0x75955e3ffc
	protected override Void OnEnter() { }
	// RVA: 0x2fcc254 VA: 0x75955e4254
	protected override Void OnResume() { }
	// RVA: 0x2fcc104 VA: 0x75955e4104
	private Void _InitIfNot() { }
	// RVA: 0x2fcc39c VA: 0x75955e439c
	private Void _InitDecodeView(String zoneId) { }
	// RVA: 0x2fcc680 VA: 0x75955e4680
	private Void _CloseZoneRecord() { }
	// RVA: 0x2fcc854 VA: 0x75955e4854
	public Void .ctor() { }
	// RVA: 0x2fcc8c4 VA: 0x75955e48c4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fcc8cc VA: 0x75955e48cc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```