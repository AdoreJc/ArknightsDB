# ActMultiV3PhotoViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `Int32 photoTypeIdx`

- `String photoTemplateId`

- `String photoInstId`

- `Int32 sortId`

- `Boolean containPhoto`

- `Boolean hasTrackPoint`

- `String photoTypeName`

- `String photoBg`


## Methods

- `Boolean _CheckTrackPoint(String, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 photoTypeIdx; // 0x18
	public String photoTemplateId; // 0x20
	public String photoInstId; // 0x28
	public Int32 sortId; // 0x30
	public Boolean containPhoto; // 0x34
	public Boolean hasTrackPoint; // 0x35
	public String photoTypeName; // 0x38
	public String photoBg; // 0x40
	public List`1 charModels; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__CheckTrackPoint; // 0x8


	// RVA: 0x31232c8 VA: 0x759573b2c8
	public Void .ctor(String actId, String templateId, String photoInstId, ActMultiV3PhotoTypeData photoTypeData, Photo photo) { }
	// RVA: 0x31237f8 VA: 0x759573b7f8
	private Boolean _CheckTrackPoint(String actId, Dictionary`2 photoCollection) { }
}
```