<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "8311f46a35cf608c9780f39b62c9dc3f",
  "translation_date": "2025-06-12T21:43:36+00:00",
  "source_file": "05-AdvancedTopics/mcp-root-contexts/README.md",
  "language_code": "ko"
}
-->
## 루트 컨텍스트 모범 사례

루트 컨텍스트를 효과적으로 관리하기 위한 몇 가지 모범 사례는 다음과 같습니다:

- **목적에 맞는 컨텍스트 생성**: 명확성을 유지하기 위해 서로 다른 대화 목적이나 도메인별로 별도의 루트 컨텍스트를 만드세요.

- **만료 정책 설정**: 저장 공간을 관리하고 데이터 보존 정책을 준수하기 위해 오래된 컨텍스트를 아카이브하거나 삭제하는 정책을 구현하세요.

- **관련 메타데이터 저장**: 나중에 유용할 수 있는 대화에 관한 중요한 정보를 컨텍스트 메타데이터에 저장하세요.

- **컨텍스트 ID 일관되게 사용**: 컨텍스트가 생성된 후에는 관련된 모든 요청에 대해 해당 ID를 일관되게 사용하여 연속성을 유지하세요.

- **요약 생성**: 컨텍스트가 커질 경우, 중요한 정보를 요약하여 컨텍스트 크기를 관리하는 방안을 고려하세요.

- **접근 제어 구현**: 다중 사용자 시스템에서는 대화 컨텍스트의 개인정보 보호와 보안을 위해 적절한 접근 제어를 구현하세요.

- **컨텍스트 제한 사항 처리**: 컨텍스트 크기 제한을 인지하고, 매우 긴 대화를 처리할 전략을 마련하세요.

- **완료 시 아카이브**: 대화가 완료되면 리소스를 확보하고 대화 기록을 보존하기 위해 컨텍스트를 아카이브하세요.

## 다음 단계

- [5.5 라우팅](../mcp-routing/README.md)

**면책 조항**:  
이 문서는 AI 번역 서비스 [Co-op Translator](https://github.com/Azure/co-op-translator)를 사용하여 번역되었습니다. 정확성을 위해 최선을 다하고 있으나, 자동 번역에는 오류나 부정확성이 포함될 수 있음을 유의해 주시기 바랍니다. 원문 문서가 권위 있는 출처로 간주되어야 합니다. 중요한 정보의 경우 전문적인 인간 번역을 권장합니다. 본 번역 사용으로 인해 발생하는 오해나 잘못된 해석에 대해 당사는 책임을 지지 않습니다.