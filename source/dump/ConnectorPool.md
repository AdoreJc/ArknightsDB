# ConnectorPool

**Namespace:** ` `


## Fields

- `SandboxV2NodeViewHome m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ConnectorPool : GameObjectDictPool`1
{
	private SandboxV2NodeViewHome m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x2568bac VA: 0x7594b80bac
	public Void .ctor(SandboxV2NodeViewHome closure) { }
	// RVA: 0x25691bc VA: 0x7594b811bc
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x25692f0 VA: 0x7594b812f0
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x25693e0 VA: 0x7594b813e0
	protected override RectTransform GetPrefab(String key) { }
	// RVA: 0x25694ac VA: 0x7594b814ac
	protected override RectTransform Instantiate(String key, RectTransform prefab) { }
	// RVA: 0x2569580 VA: 0x7594b81580
	protected override Void Render(String key, RectTransform obj) { }
}
```