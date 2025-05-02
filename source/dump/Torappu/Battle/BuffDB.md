# BuffDB

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean TryGetTemplate(String, out)`

- `Void LoadBuffTemplatesIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BuffDB : SimpleKVTable`2
{
	private Dictionary`2 m_buffTemplates; // 0x68
	private static DelegateBridge __Hotfix0_TryGetTemplate; // 0x0
	private static DelegateBridge __Hotfix0_LoadBuffTemplatesIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1c55454 VA: 0x759426d454
	public Boolean TryGetTemplate(String templateKey, out BuffTemplate template) { }
	// RVA: 0x1c55510 VA: 0x759426d510
	public Void LoadBuffTemplatesIfNot() { }
	// RVA: 0x1c555e4 VA: 0x759426d5e4
	protected override Void OnInit() { }
	// RVA: 0x1c55654 VA: 0x759426d654
	public Void .ctor() { }
}
```