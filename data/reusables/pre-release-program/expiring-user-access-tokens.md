{% ifversion ghes < 3.1 %}
{% note %}

**Note:** Expiring user tokens are currently part of the user-to-server token expiration beta and subject to change. To opt-in to the user-to-server token expiration beta feature, see "[Activating optional features for apps](/developers/apps/activating-optional-features-for-apps)." For more information, see "[Expiring user-to-server access tokens for GitHub Apps](https://developer.github.com/changes/2020-04-30-expiring-user-to-server-access-tokens-for-github-apps)."

{% endnote %}

{% elsif fpt or ghes > 3.0 or ghae %}

{% note %}

**Note:** Expiring user tokens are currently an optional feature and subject to change. To opt in or out of the user-to-server token expiration feature, see "[Activating optional features for apps](/developers/apps/activating-optional-features-for-apps)." For more information, see "[Expiring user-to-server access tokens for GitHub Apps](https://developer.github.com/changes/2020-04-30-expiring-user-to-server-access-tokens-for-github-apps)."

{% endnote %}

{% endif %}
