# CarvingMainRoundEndStateBean

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMainRoundEndProperty m_prop`


## Properties

- `CarvingMainRoundEndProperty prop`


## Methods

- `CarvingMainRoundEndProperty get_prop()`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainRoundEndStateBean : IStateBean, IHotfixable
{
	private CarvingMainRoundEndProperty m_prop; // 0x10
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public CarvingMainRoundEndProperty prop { get; }

	// RVA: 0x2db4b58 VA: 0x75953ccb58
	public CarvingMainRoundEndProperty get_prop() { }
	// RVA: 0x2db543c VA: 0x75953cd43c
	public Void LoadData(String actId) { }
	// RVA: 0x2db596c VA: 0x75953cd96c
	public Void .ctor() { }
}
```