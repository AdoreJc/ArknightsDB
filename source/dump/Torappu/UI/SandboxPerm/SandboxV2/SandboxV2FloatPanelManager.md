# SandboxV2FloatPanelManager

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2FloatPanel m_currActiveFloatPanel`


## Methods

- `Void _CheckTouchingFloatPanel(Vector3)`

- `Void Watch(SandboxV2FloatPanel)`

- `Void Unwatch(SandboxV2FloatPanel)`

- `Void OnFloatPanelShown(SandboxV2FloatPanel)`

- `Void OnFloatPanelHidden(SandboxV2FloatPanel)`

- `Void ClearFloatPanel()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2FloatPanelManager : MonoBehaviour, IHotfixable
{
	private List`1 m_lastTouchIdList; // 0x18
	private List`1 m_raycastResults; // 0x20
	private HashSet`1 m_floatPanels; // 0x28
	private SandboxV2FloatPanel m_currActiveFloatPanel; // 0x30
	private static DelegateBridge __Hotfix0__CheckTouchingFloatPanel; // 0x0
	private static DelegateBridge __Hotfix0_Watch; // 0x8
	private static DelegateBridge __Hotfix0_Unwatch; // 0x10
	private static DelegateBridge __Hotfix0_OnFloatPanelShown; // 0x18
	private static DelegateBridge __Hotfix0_OnFloatPanelHidden; // 0x20
	private static DelegateBridge __Hotfix0_ClearFloatPanel; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x24fefcc VA: 0x7594b16fcc
	private Void _CheckTouchingFloatPanel(Vector3 touchPosition) { }
	// RVA: 0x24fec30 VA: 0x7594b16c30
	public Void Watch(SandboxV2FloatPanel element) { }
	// RVA: 0x24fee34 VA: 0x7594b16e34
	public Void Unwatch(SandboxV2FloatPanel element) { }
	// RVA: 0x24fe6d0 VA: 0x7594b166d0
	public Void OnFloatPanelShown(SandboxV2FloatPanel element) { }
	// RVA: 0x24fe918 VA: 0x7594b16918
	public Void OnFloatPanelHidden(SandboxV2FloatPanel element) { }
	// RVA: 0x24ff288 VA: 0x7594b17288
	public Void ClearFloatPanel() { }
	// RVA: 0x24ff474 VA: 0x7594b17474
	private Void Update() { }
	// RVA: 0x24ff654 VA: 0x7594b17654
	public Void .ctor() { }
}
```