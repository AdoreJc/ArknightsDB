# SandboxV2LogisticsHomeStateBean

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2LogisticsHomeProperty viewProperty`

- `String m_topicId`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void LoadData(Param)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsHomeStateBean : IHotfixable
{
	public SandboxV2LogisticsHomeProperty viewProperty; // 0x10
	private String m_topicId; // 0x18
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String topicId { get; }

	// RVA: 0x25d95a0 VA: 0x7594bf15a0
	public String get_topicId() { }
	// RVA: 0x25d8960 VA: 0x7594bf0960
	public Void LoadData(Param pageParam) { }
	// RVA: 0x25dafd0 VA: 0x7594bf2fd0
	public Void .ctor() { }
}
```