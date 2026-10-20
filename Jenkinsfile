boolean disableIndexTriggers = env.BRANCH_NAME != 'main'

quadletPipeline(
    disableIndexTriggers: disableIndexTriggers,
    podmanSecretMappings: [
        [
            type: 'string',
            credentialsId: 'ntfy-auth-users',
            podmanSecretStringName: 'ntfy_auth_users'
        ]
    ]
)
