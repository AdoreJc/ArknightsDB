# CarvingMainProcessFrameModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String card`

- `Int32 score`

- `ProcessFrameType frameType`

- `Boolean isTriggerBonus`

- `Int32 cardBounceSeq`


## Methods

- `Void LoadFrame(Act35SideData, CarvingProcessFrame)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainProcessFrameModel : IHotfixable
{
	public String card; // 0x10
	public List`1 outputList; // 0x18
	public Int32 score; // 0x20
	public ProcessFrameType frameType; // 0x24
	public Boolean isTriggerBonus; // 0x28
	public Int32 cardBounceSeq; // 0x2c
	private static DelegateBridge __Hotfix0_LoadFrame; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d9d154 VA: 0x75953b5154
	public Void LoadFrame(Act35SideData actData, CarvingProcessFrame frame) { }
	// RVA: 0x2d9d088 VA: 0x75953b5088
	public Void .ctor() { }
}
```