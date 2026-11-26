## VibeFinder 0.9.9 Beta — Release notes

### Library scanning and metadata

- **The biggest change in this update is more complete metadata indexing.** Earlier scans could miss metadata in some files, leaving matching samples out of searches by manufacturer and other fields.
- **After updating, right-click each existing library and choose `Force Rescan` to refresh its metadata.** This is especially important if you use metadata to find or organize samples.
- Waveform previews are generated first for samples that are visible in the results or that you select.

### Sample search and autocomplete

- Type `#` followed by a search term to add a suggested filter as a tag. For example, `#96` suggests the 96 kHz sample rate.
- Use `#tag` to find saved tags and `#library` to find scanned folders directly from the search field.
- Type `#` on its own to bring back frequent or recently used filters. VibeFinder remembers up to **1,048** entries. Choose **Show more** to see 10 more at a time.

### Detach and rearrange sections

- Drag a section header to move it into its own window, place it on another monitor, or dock it around the sample list, much like arranging panels in Unreal Engine or REAPER.
- Seven sections support this layout: Library, Tags, Related Tags, Folders, Waveform, Sample Info and Audio File Metadata. Your layout is restored the next time you open VibeFinder.

### Fit sample columns to the panel

- **Hold Ctrl+Shift and double-click the divider between two column headers** to fit all visible columns to the width of the Sample section. Columns keep their relative widths, with horizontal scrolling needed only if the panel is too narrow for their minimum widths.

---

## VibeFinder 0.9.9 Beta 패치노트

### 라이브러리 스캔 및 메타데이터 개선

- **이번 업데이트의 가장 큰 변경점입니다.** 기존 라이브러리를 스캔할 때 일부 파일의 메타데이터가 누락되어, 제조업체 등의 정보로 검색해도 해당 샘플이 결과에 나타나지 않던 문제를 개선했습니다.
- **업데이트 후 기존 라이브러리를 각각 우클릭해 `Force Rescan`을 실행해 주세요.** 기존 파일의 메타데이터까지 갱신됩니다. 특히 메타데이터로 샘플을 찾고 분류하는 분들께 권장합니다.
- 검색 결과의 파형 미리보기는 현재 화면에 보이는 샘플과 직접 선택한 샘플부터 우선 생성합니다.

### 신규 기능 · 샘플 검색 및 자동완성

- 검색창에 `#`과 검색어를 입력하면 추천 조건을 **태그 형태로 추가**할 수 있습니다. 예를 들어 `#96`을 입력하면 96 kHz 샘플레이트 조건이 추천됩니다.
- `#tag`로 저장한 태그를, `#library`로 스캔한 폴더를 검색창에서 바로 찾아 적용할 수 있습니다.
- `#`만 입력하면 자주 사용했거나 최근에 적용한 검색 조건을 빠르게 다시 선택할 수 있습니다. 사용 기록은 최대 **1,048개**까지 저장되며, **더보기**를 누르면 10개씩 추가로 표시됩니다.

### 신규 기능 · 섹션 창 분리 및 재배치

- Unreal Engine이나 REAPER처럼 **섹션 헤더를 드래그해 작업 화면을 구성**할 수 있습니다. 섹션을 독립 창으로 꺼내 다른 모니터로 옮기거나, 샘플 목록 주변으로 다시 드래그해 원하는 위치에 붙일 수 있습니다.
- **라이브러리, 태그, 관련 태그, 폴더, 파형, 샘플 정보, 오디오 파일 메타데이터**의 7개 섹션을 지원합니다. 변경한 배치는 다음 실행 시에도 복원됩니다.

### 샘플 섹션 · 열 너비 자동 조정

- 샘플 목록에서 **Ctrl+Shift를 누른 채 열 머리글 사이의 경계선을 더블클릭**하면 표시 중인 모든 열이 현재 샘플 섹션의 너비에 맞춰집니다. 기존 열 너비 비율을 유지하며, 열의 최소 너비를 모두 담을 수 있는 화면에서는 가로 스크롤 없이 볼 수 있습니다.
