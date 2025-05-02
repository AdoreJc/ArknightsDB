# BattleNotification

**Namespace:** `Torappu.Battle.UI`


## Fields

- `RectTransform _notifyFloatLayout`

- `HostImpl m_host`


## Methods

- `Boolean AddNotifyView(NotifyViewOptions`2)`

- `Void FixedUpdate()`

- `Boolean _CheckIfVisible()`

- `Void _SetVisible(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class BattleNotification : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private RectTransform _notifyFloatLayout; // 0x18
	private HostImpl m_host; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_AddNotifyView; // 0x8
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfVisible; // 0x18
	private static DelegateBridge __Hotfix0__SetVisible; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2041660 VA: 0x7594659660
	protected override Void OnInit() { }
	// RVA: 0x VA: 0x0
	public Boolean AddNotifyView(NotifyViewOptions`2 options) { }
	// RVA: 0x2041804 VA: 0x7594659804
	private Void FixedUpdate() { }
	// RVA: 0x2041898 VA: 0x7594659898
	private Boolean _CheckIfVisible() { }
	// RVA: 0x2041934 VA: 0x7594659934
	private Void _SetVisible(Boolean visible) { }
	// RVA: 0x20419c0 VA: 0x75946599c0
	public Void .ctor() { }
}
```