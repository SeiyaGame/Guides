??? abstract "Scoring des Formats Personnalisés liés aux Profils de Langue - [Cliquer pour afficher/masquer]"

    | Formats Personnalisés                                                                                                           | Trash ID                                                   |                                 Score profile VOSTFR                                  |                                Score profile MULTI.VO                                |
    | ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | :-----------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------: |
    | [{{ radarr['cf']['language-original-french']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#language-original-french) | {{ radarr['cf']['language-original-french']['trash_id'] }} | {{ radarr['cf']['language-original-french']['trash_scores']['french-anime-vostfr'] }} | {{ radarr['cf']['language-original-french']['trash_scores']['french-anime-multi'] }} |
    | [{{ radarr['cf']['language-not-original']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#language-not-original)       | {{ radarr['cf']['language-not-original']['trash_id'] }}    |  {{ radarr['cf']['language-not-original']['trash_scores']['french-anime-vostfr'] }}   |  {{ radarr['cf']['language-not-original']['trash_scores']['french-anime-multi'] }}   |
    | [{{ radarr['cf']['language-not-french']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#language-not-french)           | {{ radarr['cf']['language-not-french']['trash_id'] }}      |   {{ radarr['cf']['language-not-french']['trash_scores']['french-anime-vostfr'] }}    |   {{ radarr['cf']['language-not-french']['trash_scores']['french-anime-multi'] }}    |
    | [{{ radarr['cf']['french-vostfr']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#vostfr)                              | {{ radarr['cf']['french-vostfr']['trash_id'] }}            |      {{ radarr['cf']['french-vostfr']['trash_scores']['french-anime-vostfr'] }}       |      {{ radarr['cf']['french-vostfr']['trash_scores']['french-anime-multi'] }}       |
    | [{{ radarr['cf']['multi']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#multi)                                       | {{ radarr['cf']['multi']['trash_id'] }}                    |                                           0                                           |                                          0                                           |
    | [{{ radarr['cf']['french-anime-tier-01']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-anime-tier-01)             | {{ radarr['cf']['french-anime-tier-01']['trash_id'] }}     |   {{ radarr['cf']['french-anime-tier-01']['trash_scores']['french-anime-vostfr'] }}   |   {{ radarr['cf']['french-anime-tier-01']['trash_scores']['french-anime-multi'] }}   |
    | [{{ radarr['cf']['french-anime-tier-02']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-anime-tier-02)             | {{ radarr['cf']['french-anime-tier-02']['trash_id'] }}     |   {{ radarr['cf']['french-anime-tier-02']['trash_scores']['french-anime-vostfr'] }}   |   {{ radarr['cf']['french-anime-tier-02']['trash_scores']['french-anime-multi'] }}   |
    | [{{ radarr['cf']['french-anime-tier-03']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-anime-tier-03)             | {{ radarr['cf']['french-anime-tier-03']['trash_id'] }}     |   {{ radarr['cf']['french-anime-tier-03']['trash_scores']['french-anime-vostfr'] }}   |   {{ radarr['cf']['french-anime-tier-03']['trash_scores']['french-anime-multi'] }}   |
    | [{{ radarr['cf']['french-scene']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-scene-groups)                      | {{ radarr['cf']['french-scene']['trash_id'] }}             |       {{ radarr['cf']['french-scene']['trash_scores']['french-anime-vostfr'] }}       |       {{ radarr['cf']['french-scene']['trash_scores']['french-anime-multi'] }}       |
    | [{{ radarr['cf']['french-anime-fansub']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-anime-fansub)               | {{ radarr['cf']['french-anime-fansub']['trash_id'] }}      |   {{ radarr['cf']['french-anime-fansub']['trash_scores']['french-anime-vostfr'] }}    |   {{ radarr['cf']['french-anime-fansub']['trash_scores']['french-anime-multi'] }}    |
    | [{{ radarr['cf']['french-hd-bluray-tier-01']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-hd-bluray-tier-01)     | {{ radarr['cf']['french-hd-bluray-tier-01']['trash_id'] }} | {{ radarr['cf']['french-hd-bluray-tier-01']['trash_scores']['french-anime-vostfr'] }} | {{ radarr['cf']['french-hd-bluray-tier-01']['trash_scores']['french-anime-multi'] }} |
    | [{{ radarr['cf']['french-hd-bluray-tier-02']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-hd-bluray-tier-02)     | {{ radarr['cf']['french-hd-bluray-tier-02']['trash_id'] }} | {{ radarr['cf']['french-hd-bluray-tier-02']['trash_scores']['french-anime-vostfr'] }} | {{ radarr['cf']['french-hd-bluray-tier-02']['trash_scores']['french-anime-multi'] }} |
    | [{{ radarr['cf']['french-web-tier-01']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-web-tier-01)                 | {{ radarr['cf']['french-web-tier-01']['trash_id'] }}       |    {{ radarr['cf']['french-web-tier-01']['trash_scores']['french-anime-vostfr'] }}    |    {{ radarr['cf']['french-web-tier-01']['trash_scores']['french-anime-multi'] }}    |
    | [{{ radarr['cf']['french-web-tier-02']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-web-tier-02)                 | {{ radarr['cf']['french-web-tier-02']['trash_id'] }}       |    {{ radarr['cf']['french-web-tier-02']['trash_scores']['french-anime-vostfr'] }}    |    {{ radarr['cf']['french-web-tier-02']['trash_scores']['french-anime-multi'] }}    |

    !!! tip

        Les groupes de la scène française sont inclus et devraient toujours être ajoutés, car certains des principaux groupes qui publient des versions sous-titrées et/ou doublées en français en sont issus.

        Les groupes FanSUB peuvent être notés soit {{ radarr['cf']['french-anime-fansub']['trash_scores']['default'] }} (par défaut) soit `1000`, selon que vous souhaitez privilégier les sorties FanSUB ou SeaDex.

    !!! tip "Original French Bluray/Web Tiers"

        Ils sont optionnels et peuvent être inclus ou non. Cela est dû au fait que certains d'entre eux ont tendance à publier des anime.

    !!! tip "Score Profile VOSTFR"

        Le Format Personnalisé [{{ radarr['cf']['multi']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#multi) est dispensable pour le profil `VOSTFR`. En effet il est utilisé dans le but de renommer les fichiers afin de conserver le score attribué par le format personnalisé [{{ radarr['cf']['language-original-french']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#language-original-french).

        Si vous voulez que le profil `VOSTFR` prenne aussi les release MULTI dans le cas ou aucune release VOSTFR n'est disponible, il faut donc mettre la valeur de [{{ radarr['cf']['language-original-french']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#language-original-french) à `0` au lieu de `{{ radarr['cf']['language-original-french']['trash_scores']['french-anime-vostfr'] }}` et importer le format personnalisé [{{ radarr['cf']['multi']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#multi)

    !!! tip "Préférer la version FanSub aux autres"

        Si vous préférez les release FanSub à n'importe quelle version des Tiers FR Anime, il faut donc mettre [{{ radarr['cf']['french-anime-fansub']['name'] }}](/Radarr/radarr-collection-of-custom-formats/#fr-anime-fansub) à `1700` au lieu de `{{ radarr['cf']['french-anime-fansub']['trash_scores']['default'] }}`