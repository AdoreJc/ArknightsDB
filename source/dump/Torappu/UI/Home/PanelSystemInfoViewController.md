# PanelSystemInfoViewController

**Namespace:** `Torappu.UI.Home`


## Methods

- `Boolean _CheckSameDisplay(DateTime, DateTime)`

- `Void _UpdateSystemInfo()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class PanelSystemInfoViewController : MonoBehaviour, IHotfixable
{
	private Text[] _curTimeLabel; // 0x18
	private Image[] _batteryImage; // 0x20
	private Sprite[] _batterySprites; // 0x28
	private Nullable`1 m_cachedShowTime; // 0x30
	private static DelegateBridge __Hotfix0__CheckSameDisplay; // 0x0
	private static DelegateBridge __Hotfix0__UpdateSystemInfo; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2848b40 VA: 0x7594e60b40
	private Boolean _CheckSameDisplay(DateTime lhs, DateTime rhs) { }
	// RVA: 0x2848cf0 VA: 0x7594e60cf0
	private Void _UpdateSystemInfo() { }
	// RVA: 0x2849058 VA: 0x7594e61058
	private Void Update() { }
	// RVA: 0x28490c0 VA: 0x7594e610c0
	public Void .ctor() { }
}
```