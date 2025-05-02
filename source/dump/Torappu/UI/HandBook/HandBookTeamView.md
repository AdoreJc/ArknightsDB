# HandBookTeamView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Text _teamName`

- `Text _teamPercent`

- `Text _teamFavorPoint`

- `Image _teamBackground`

- `Animator _canvasControl`

- `LineRenderer _linerender`

- `Vector3 m_initPos`

- `Vector3 m_initDest`

- `Image m_teamICON`

- `Vector3 m_largeImageDest`

- `Transform m_largeImage`

- `Int32 teamType`


## Properties

- `Vector3 initPos`

- `Vector3 initDest`

- `Vector3 largeImageInitPos`

- `Transform largeImage`


## Methods

- `Vector3 get_initPos()`

- `Void set_initPos(Vector3)`

- `Vector3 get_initDest()`

- `Void set_initDest(Vector3)`

- `Void set_largeImageInitPos(Vector3)`

- `Vector3 get_largeImageInitPos()`

- `Void set_largeImage(Transform)`

- `Transform get_largeImage()`

- `Void InitData(HandbookTeamData, HandbookTeamIconData, Single, Int32, Sprite)`

- `Void UnShow()`

- `Void OnValueChanged(HandBookScrollViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookTeamView : MonoBehaviour
{
	private Text _teamName; // 0x18
	private Text _teamPercent; // 0x20
	private Text _teamFavorPoint; // 0x28
	private Image _teamBackground; // 0x30
	private Image[] _lines; // 0x38
	private Transform[] _linePoints; // 0x40
	private Image[] _teamImage; // 0x48
	private Animator _canvasControl; // 0x50
	private LineRenderer _linerender; // 0x58
	private Vector3 m_initPos; // 0x60
	private Vector3 m_initDest; // 0x6c
	private Image m_teamICON; // 0x78
	private Vector3 m_largeImageDest; // 0x80
	private Transform m_largeImage; // 0x90
	private Int32 teamType; // 0x98

	public Vector3 initPos { get; set; }
	public Vector3 initDest { get; set; }
	private Vector3 largeImageInitPos { get; set; }
	private Transform largeImage { get; set; }

	// RVA: 0x2eb6798 VA: 0x75954ce798
	public Vector3 get_initPos() { }
	// RVA: 0x2eb67a4 VA: 0x75954ce7a4
	public Void set_initPos(Vector3 value) { }
	// RVA: 0x2eb67b0 VA: 0x75954ce7b0
	public Vector3 get_initDest() { }
	// RVA: 0x2eb67bc VA: 0x75954ce7bc
	public Void set_initDest(Vector3 value) { }
	// RVA: 0x2eb67c8 VA: 0x75954ce7c8
	public Void set_largeImageInitPos(Vector3 value) { }
	// RVA: 0x2eb67d4 VA: 0x75954ce7d4
	private Vector3 get_largeImageInitPos() { }
	// RVA: 0x2eb67e0 VA: 0x75954ce7e0
	public Void set_largeImage(Transform value) { }
	// RVA: 0x2eb67e8 VA: 0x75954ce7e8
	private Transform get_largeImage() { }
	// RVA: 0x2eb45a8 VA: 0x75954cc5a8
	public Void InitData(HandbookTeamData teamInfo, HandbookTeamIconData teamData, Single teamPercent, Int32 teamPoint, Sprite teamICON) { }
	// RVA: 0x2eb51f0 VA: 0x75954cd1f0
	public Void UnShow() { }
	// RVA: 0x2eb5448 VA: 0x75954cd448
	public Void OnValueChanged(HandBookScrollViewProperty property) { }
	// RVA: 0x2eb67f0 VA: 0x75954ce7f0
	public Void .ctor() { }
}
```