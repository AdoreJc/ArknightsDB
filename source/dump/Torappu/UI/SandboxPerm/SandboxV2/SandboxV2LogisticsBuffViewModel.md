# SandboxV2LogisticsBuffViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `ProfessionCategory profession`

- `Int32 totalCount`

- `Int32 maxValidCount`

- `String baseDesc`

- `String buffParam`


## Properties

- `Boolean isFullBuff`

- `String combinedDesc`


## Methods

- `Boolean get_isFullBuff()`

- `String get_combinedDesc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsBuffViewModel : IHotfixable
{
	public ProfessionCategory profession; // 0x10
	public Int32 totalCount; // 0x14
	public Int32 maxValidCount; // 0x18
	public String baseDesc; // 0x20
	public String buffParam; // 0x28
	private static DelegateBridge __Hotfix0_get_isFullBuff; // 0x0
	private static DelegateBridge __Hotfix0_get_combinedDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isFullBuff { get; }
	public String combinedDesc { get; }

	// RVA: 0x25dc2f8 VA: 0x7594bf42f8
	public Boolean get_isFullBuff() { }
	// RVA: 0x25dc034 VA: 0x7594bf4034
	public String get_combinedDesc() { }
	// RVA: 0x25de8b8 VA: 0x7594bf68b8
	public Void .ctor() { }
}
```