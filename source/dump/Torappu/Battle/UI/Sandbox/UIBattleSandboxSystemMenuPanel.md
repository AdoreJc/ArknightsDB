# UIBattleSandboxSystemMenuPanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UIBattleSandboxSysMenuStyle _defaultMenuStyle`

- `UIBattleSandboxSysMenuStyle _finishGameMenuStyle`

- `Single _fadeInTime`

- `UIBattleSandboxSysMenuStyle m_curMenuStyle`

- `CanvasGroup m_canvasGroup`

- `SandboxUIPlugin m_plugin`


## Methods

- `Void OnInit()`

- `Void SetData()`

- `Void Hide()`

- `Void Show()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxSystemMenuPanel : MonoBehaviour, IHotfixable
{
	private UIBattleSandboxSysMenuStyle _defaultMenuStyle; // 0x18
	private UIBattleSandboxSysMenuStyle _finishGameMenuStyle; // 0x20
	private Single _fadeInTime; // 0x28
	private UIBattleSandboxSysMenuStyle m_curMenuStyle; // 0x30
	private CanvasGroup m_canvasGroup; // 0x38
	private SandboxUIPlugin m_plugin; // 0x40
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x209d424 VA: 0x75946b5424
	public Void OnInit() { }
	// RVA: 0x209d680 VA: 0x75946b5680
	public Void SetData() { }
	// RVA: 0x209d5dc VA: 0x75946b55dc
	public Void Hide() { }
	// RVA: 0x209d928 VA: 0x75946b5928
	public Void Show() { }
	// RVA: 0x209da7c VA: 0x75946b5a7c
	private Void Awake() { }
	// RVA: 0x209db0c VA: 0x75946b5b0c
	public Void .ctor() { }
}
```