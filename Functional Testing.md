# Functional Testing

## UAT (User Acceptance Test)
UAT(User Acceptance Test)는 소프트웨어가 비즈니스 및 사용자 요구사항을 충족하는지 확인하기 위해 최종 사용자 또는 이해관계자가 수행하는 테스트 유형이다.   
UAT는 실제 시나리오에서 애플리케이션을 테스트하는 것을 포함하며, 애플리케이션을 구현하기 전에 테스트하는 최종 단계이다.    
UAT의 목표는 애플리케이션이 사용자의 기대를 충족하고 출시 준비가 되었는지 확인하는 것이다.

## 장단점
### 장점
* 사용자의 요구사항 및 비즈니스 요구사항을 충족하도록 지원한다.
* 최종 사용자와 이해 관계자로부터 피드백을 제공받는다.
* 이전 테스트 단계에서 감지되지 않았을 수 있는 가용성 문제 및 기타 문제를 식별할 수 있도록 지원한다.
* 애플리케이션에 대한 사용자 신뢰도를 높인다.

### 단점
* 시간이 많이 걸리고 비용이 많이 들 수 있다.
* 전문적인 도구와 지식이 필요할 수 있다.
* 최종 사용자와 이해 관계자가 모든 유형의 문제를 식별할 수 있는 기술적 전문 지식을 가지고 있지 않을 수 있다.
* UAT 중에 문제가 발견되면 응용 프로그램의 릴리스가 지연될 수 있다.

## Exploratory Test
Exploratory Test(탐색적 테스트)는 미리 정의된 테스트 계획이나 스크립트 없이 수행되는 테스트 유형이다.   
테스터는 프로그램과 상호작용하고 결함과 문제를 찾아 프로그램을 탐색한다.   
Exploratory Test는 일반적으로 응용프로그램과 사용자를 이해하는 숙련된 테스터가 수행한다.

## 장단점
### 장점
* 다른 유형의 테스트를 통해 발견할 수 없는 결함 및 문제를 발견할 수 있다.
* 가장 중요한 결함을 찾는 데 중점을 두기 때문에 다른 유형의 테스트보다 효율적일 수 있다.
* 사용자 경험에 대한 통찰력을 제공할 수 있다.

### 단점
* 다른 유형의 테스트보다 반복성이 낮을 수 있다.
* 결함 및 문제를 추적하고 보고하는 것이 어려울 수 있다.
* 가능한 모든 시나리오를 다루지 않을 수 있다.

## Sanity Test (온전성 테스트)
Sanity Test(온전성 테스트)는 사소한 변경 후 애플리케이션이 예상대로 작동하는지 신속하게 확인하기 위해 수행되는 테스트의 유형이다.  
Sanity Test의 목표는 애플리케이션의 가장 중요한 기능이 변경된 후에도 계속 작동하는지 확인하는 것이다.

## 장단점
### 장점
* 변경 사항이 애플리케이션에 영향을 미쳤는지 신속하게 확인할 수 있다.
* 시간을 절약하고 효율성을 높이기 위해 자동화할 수 있다.
* 변경 후 테스트 작업의 우선순위를 정하는 데 사용할 수 있다.

### 단점
* 복잡한 변경이나 기능에는 충분하지 않을 수 있다.
* 모든 문제를 파악할 수 있을 정도로 포괄적이지 않을 수 있다.
* 애플리케이션의 모든 영역이 예상대로 작동하는지 확인하기 위해 추가 테스트가 필요할 수 있다.

## Regression Test (회귀 테스트)
Regression Test(회귀 테스트)는 프로그램의 다른 영역에서 의도하지 않은 영향이나 결함을 발생시키지 않도록 프로그램을 변경하기 위해 수행되는 테스트의 유형이다.   
Regression Test에서는 이전에 테스트한 기능을 다시 테스트하여 예상대로 작동하는지 확인한다.

## 장단점
### 장점
* 변경사항이 의도하지 않은 영향을 미치지 않도록 보장한다.
* 이전 테스트 단계에서 누락되었을 수 있는 결함 및 문제를 파악할 수 있다.
* 시간이 지남에 따라 애플리케이션의 안정성에 대한 데이터를 제공할 수 있다.

### 단점
* 시간이 많이 걸리고 비용이 많이 들 수 있다.
* 테스트 사례가 제대로 업데이트되거나 유지되지 않으면 효과가 떨어질 수 있다.
* 발생할 수 있는 모든 결함 또는 문제를 파악하지 못할 수 있다.

## Smoke Test (스모크 테스트)
Smoke Test(스모크 테스트)는 코드를 크게 변경한 후 시스템의 기본 기능이 제대로 작동하는지 확인하는 데 사용되는 테스트 유형이다.   
Smoke Test(스모크 테스트)는 상세한 테스트를 진행하기 전에 애플리케이션의 중요한 기능을 확인하는 고급 테스트 접근 방식이다.   
추가 테스트를 위해 시스템이 안정적인지 확인하기 위해 수행된다.    

## 장단점
### 장점
* 개발 프로세스 초기에 주요 결함을 식별하는 데 도움이 된다.
* 복잡해지기 전에 문제를 파악하여 시간과 리소스를 절약할 수 있다.
* 쉽게 자동화할 수 있습니다.

### 단점
* 시스템의 기본 기능만 점검한다.
* 보이지 않는 중요한 결함들을 놓칠 수 있다.
* 시스템 동작에 대한 자세한 정보를 제공하지 않는다.

## Unit Test (단위 테스트)
Unit Test(단위 테스트)는 함수와 같은 코드의 최소 단위를 확인하기 위해 수행되는 테스트 유형이다.   
코드의 단위가 예상대로 작동하는지 확인하기 위해 개발자가 코딩 단계에서 수행한다.   
Unit Test(단위 테스트)는 자동화되며 CI 프로세스에 통합될 수 있다.

## 장단점
### 장점
* 개발 프로세스 초기에 결함을 식별할 수 있다.
* 개발자에게 코드 품질에 대한 빠른 피드백을 제공한다.
* 개발자가 코드 단위에 대해 독립적으로 생각하도록 하여 시스템 설계를 개선하는 데 도움이 된다.

### 단점
* 복잡한 기능을 테스트하는 경우 시간이 많이 소요될 수 있다.
* 개발자는 시스템에 대해 광범위하게 이해하지 못할 수 있어 중요한 문제를 놓칠 수 있다.

## Integration Test (통합 테스트)
Integration Test(통합 테스트)는 시스템의 여러 모듈 간 상호 작용을 확인하기 위해 수행되는 테스트 유형이다.   
테스트가 완료된 후 개별 장치가 예상대로 함께 작동하는지 확인하기 위해 수행된다.   
Integration Test(통합 테스트)는 시스템 아키텍처에 따라 하향식 또는 상향식과 같은 다양한 방법으로 수행할 수 있다.

## 장단점
### 장점
* 서로 다른 모듈의 상호 작용으로 인해 발생하는 결점을 식별하는 데 도움이 된다.
* 시스템이 개별 장치의 집합이 아니라 전체적으로 작동하도록 보장한다.
* 다양한 조건에서 시스템의 동작에 대한 피드백을 제공한다.

### 단점
* 많은 모듈을 테스트하는 경우 복잡하고 시간이 많이 소요될 수 있다.
* 통합 검정에서 다루지 않는 교호작용으로 인해 발생하는 결점을 놓칠 수 있다.
* 결함의 원인에 대한 자세한 정보를 제공하지 않을 수 있다.

### 참고
https://en.wikipedia.org/wiki/Acceptance_testing   
https://en.wikipedia.org/wiki/Exploratory_testing   
https://en.wikipedia.org/wiki/Sanity_check   
https://en.wikipedia.org/wiki/Regression_testing   
https://en.wikipedia.org/wiki/Smoke_testing_(software)    
https://en.wikipedia.org/wiki/Unit_testing    
https://en.wikipedia.org/wiki/Integration_testing    