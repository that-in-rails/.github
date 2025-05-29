# that-in-rails

Welcome to that-in-rails - a collection of Ruby on Rails projects demonstrating best practices and patterns for building sustainable Rails applications.

## 🎯 Our Mission

We aim to showcase real-world Rails applications that follow industry best practices around:

- Code organization and architecture
- Testing strategies 
- Security practices
- Performance optimization
- Developer experience

## 🔒 Security & Environment Variables

All our projects follow secure environment variable management:

1. **Development/Test Environment**
   - Uses `dotenv-rails` gem for local development
   - Sample `.env.example` files provided
   - Actual `.env` files git-ignored

2. **Production Environment** 
   - Sensitive data stored in Rails credentials
   - Environment-specific credentials encrypted
   - Master key stored securely outside of source control
   - Infrastructure config via environment variables

Example `.env.example`:
