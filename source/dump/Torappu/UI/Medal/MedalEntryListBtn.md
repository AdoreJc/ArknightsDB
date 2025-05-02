# MedalEntryListBtn

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Text _countPart`

- `UICommonTrackPoint _medalTrackPoint`

- `TrackPointViewProperty m_medalTrackModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalEntryListBtn : MonoBehaviour, IHotfixable
{
	private Text _countPart; // 0x18
	private UICommonTrackPoint _medalTrackPoint; // 0x20
	private TrackPointViewProperty m_medalTrackModel; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27a8b90 VA: 0x7594dc0b90
	private Void _InitIfNot() { }
	// RVA: 0x27a8c30 VA: 0x7594dc0c30
	public Void Render(Int32 haveCount, Int32 totalCount) { }
	// RVA: 0x27a8d5c VA: 0x7594dc0d5c
	public Void .ctor() { }
}
```