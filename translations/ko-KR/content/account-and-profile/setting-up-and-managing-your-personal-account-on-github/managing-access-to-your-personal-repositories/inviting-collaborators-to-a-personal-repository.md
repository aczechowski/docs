---
title: 개인 리포지토리에 협력자 초대
intro: '개인 리포지토리에 협력자{% ifversion fpt or ghec %}가 되도록 사용자를 초대{% else %}로서 추가{% endif %}할 수 있습니다.'
redirect_from:
  - /articles/how-do-i-add-a-collaborator
  - /articles/adding-collaborators-to-a-personal-repository
  - /articles/inviting-collaborators-to-a-personal-repository
  - /github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository
  - /github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository
  - /account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository
product: '{% data reusables.gated-features.user-repo-collaborators %}'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
  - Repositories
shortTitle: Invite collaborators
ms.openlocfilehash: ddf095667b8125fc02fb46229f172fc36613dd31
ms.sourcegitcommit: d697e0ea10dc076fd62ce73c28a2b59771174ce8
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/20/2022
ms.locfileid: '148098485'
---
조직이 소유한 리포지토리는 보다 세부적인 액세스 권한을 부여할 수 있습니다. 자세한 내용은 “[{% data variables.product.prodname_dotcom %}에 대한 액세스 권한](/articles/access-permissions-on-github)”을 참조하세요.

{% data reusables.organizations.org-invite-expiration %}

{% ifversion fpt or ghec %}

{% 데이터 variables.enterprise.prodname_emu_enterprise %}의 구성원인 경우 회사의 다른 구성원만 초대하여 공동 작업할 수 있습니다. {% data reusables.enterprise-accounts.emu-more-info-account %}

{% note %}

**참고:** {% data variables.product.company_short %}는 24시간 이내에 리포지토리에 초대할 수 있는 사용자 수를 제한합니다. 이 제한을 초과하는 경우 24시간을 기다리거나 더 많은 사용자와 협업할 조직을 만듭니다.

{% endnote %}

{% endif %}

1. 공동 작업자로 초대하는 사람의 사용자 이름을 요청합니다. {% ifversion fpt 또는 ghec %} 아직 사용자 이름이 없는 경우 {% 데이터 variables.product.prodname_dotcom %}에 등록할 수 있습니다. 자세한 내용은 "[새 {% 데이터 variables.product.prodname_dotcom %} 계정에 등록](/articles/signing-up-for-a-new-github-account)"을 참조하세요. {% endif %} {% data reusables.repositories.navigate-to-repo %} {% data reusables.repositories.sidebar-settings %} {% ifversion fpt 또는 ghec 또는 ghes > 3.4 또는 ghae > 3.4%} {% data reusables.repositories.click-collaborators-teams %}
1. **협력자 초대** 를 클릭합니다.
  ![“협력자 초대” 단추](/assets/images/help/repository/invite-a-collaborator-button.png)
2. 검색 필드에 초대할 사용자의 이름을 입력한 다음, 일치 항목 목록에서 이름을 클릭합니다.
  ![리포지토리에 초대할 사용자의 이름을 입력하기 위한 검색 필드](/assets/images/help/repository/manage-access-invite-search-field-user.png)
3. **리포지토리에 이름 추가** 를 클릭합니다.
    ![협력자 추가 단추](/assets/images/help/repository/add-collaborator-user-repo.png) {% else %}
5. 왼쪽 사이드바에서 **협력자** 를 클릭합니다.
![협력자가 강조 표시된 리포지토리 설정 사이드바](/assets/images/help/repository/user-account-repo-settings-collaborators.png)
6. “협력자”에서 협력자의 사용자 이름을 입력하기 시작합니다.
7. 드롭다운 메뉴에서 협력자의 사용자 이름을 선택합니다.
   ![협력자 목록 드롭다운 메뉴](/assets/images/help/repository/repo-settings-collab-autofill.png)
8. **협력자 추가** 를 클릭합니다.
   ![“협력자 추가” 단추](/assets/images/help/repository/repo-settings-collab-add.png) {% endif %} {% ifversion fpt or ghec %}
9. 사용자는 리포지토리에 초대하는 메일을 받게 됩니다. 사용자가 초대를 수락하면 협력자가 리포지토리에 액세스할 수 있습니다.
{% endif %}

## 추가 참고 자료

- "[개인 계정 리포지토리에 대한 권한 수준](/articles/permission-levels-for-a-user-account-repository/#collaborator-access-for-a-repository-owned-by-a-personal-account)"
- “[개인 리포지토리에서 협력자 제거](/articles/removing-a-collaborator-from-a-personal-repository)”
- “[협력자의 리포지토리에서 자신을 제거](/articles/removing-yourself-from-a-collaborator-s-repository)”
- “[멤버를 팀으로 구성](/organizations/organizing-members-into-teams)”
