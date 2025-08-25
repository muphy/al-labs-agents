# Contains Studio AI Agents

A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development. Each agent is an expert in their domain, ready to be invoked when their expertise is needed.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   Or manually copy all the agent files to your `~/.claude/agents/` directory.

3. **Restart Claude Code** to load the new agents.

## 🚀 Quick Start

Agents are automatically available in Claude Code. Simply describe your task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

📚 **Learn more:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Example Usage
- "Create a new app for tracking meditation habits" → `rapid-prototyper`
- "What's trending on TikTok that we could build?" → `trend-researcher`
- "Our app reviews are dropping, what's wrong?" → `feedback-synthesizer`
- "Make this loading screen more fun" → `whimsy-injector`

## 📁 Directory Structure

Agents are organized by department for easy discovery:

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
├── offrun-specialized/
│   ├── ai-training-optimizer.md
│   ├── battery-performance-guardian.md
│   ├── flutter-fitness-developer.md
│   ├── gps-fusion-expert.md
│   ├── health-connect-master.md
│   ├── interval-training-designer.md
│   ├── offline-first-architect.md
│   └── track-algorithm-specialist.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 📋 Complete Agent List

### Engineering Department (`engineering/`)
- **ai-engineer** - Integrate AI/ML features that actually ship
- **backend-architect** - Design scalable APIs and server systems
- **devops-automator** - Deploy continuously without breaking things
- **frontend-developer** - Build blazing-fast user interfaces
- **mobile-app-builder** - Create native iOS/Android experiences
- **rapid-prototyper** - Build MVPs within 6-day sprints
- **test-writer-fixer** - Write tests that catch real bugs

### Product Department (`product/`)
- **feedback-synthesizer** - Transform complaints into features
- **sprint-prioritizer** - Ship maximum value in 6 days
- **trend-researcher** - Identify viral opportunities

### Marketing Department (`marketing/`)
- **app-store-optimizer** - Dominate app store search results
- **content-creator** - Generate content across all platforms
- **growth-hacker** - Find and exploit viral growth loops
- **instagram-curator** - Master the visual content game
- **reddit-community-builder** - Win Reddit without being banned
- **tiktok-strategist** - Create shareable marketing moments
- **twitter-engager** - Ride trends to viral engagement

### Design Department (`design/`)
- **brand-guardian** - Keep visual identity consistent everywhere
- **ui-designer** - Design interfaces developers can actually build
- **ux-researcher** - Turn user insights into product improvements
- **visual-storyteller** - Create visuals that convert and share
- **whimsy-injector** - Add delight to every interaction

### Project Management (`project-management/`)
- **experiment-tracker** - Data-driven feature validation
- **project-shipper** - Launch products that don't crash
- **studio-producer** - Keep teams shipping, not meeting

### Studio Operations (`studio-operations/`)
- **analytics-reporter** - Turn data into actionable insights
- **finance-tracker** - Keep the studio profitable
- **infrastructure-maintainer** - Scale without breaking the bank
- **legal-compliance-checker** - Stay legal while moving fast
- **support-responder** - Turn angry users into advocates

### Testing & Benchmarking (`testing/`)
- **api-tester** - Ensure APIs work under pressure
- **performance-benchmarker** - Make everything faster
- **test-results-analyzer** - Find patterns in test failures
- **tool-evaluator** - Choose tools that actually help
- **workflow-optimizer** - Eliminate workflow bottlenecks

### Offrun Specialized (`offrun-specialized/`)
- **ai-training-optimizer** - Optimize AI/ML training models for fitness data
- **battery-performance-guardian** - Maximize battery life during GPS tracking
- **flutter-fitness-developer** - Build Flutter fitness apps with native performance
- **gps-fusion-expert** - Enhance GPS accuracy with sensor fusion algorithms
- **health-connect-master** - Integrate Google Health Connect and Apple HealthKit
- **interval-training-designer** - Create adaptive interval training programs
- **offline-first-architect** - Design robust offline-first mobile architectures
- **track-algorithm-specialist** - Implement advanced running track detection algorithms

## 🎁 Bonus Agents
- **studio-coach** - Rally the AI troops to excellence
- **joker** - Lighten the mood with tech humor

## 🎯 Proactive Agents

Some agents trigger automatically in specific contexts:
- **studio-coach** - When complex multi-agent tasks begin or agents need guidance
- **test-writer-fixer** - After implementing features, fixing bugs, or modifying code
- **whimsy-injector** - After UI/UX changes
- **experiment-tracker** - When feature flags are added

## 💡 Best Practices

1. **Let agents work together** - Many tasks benefit from multiple agents
2. **Be specific** - Clear task descriptions help agents perform better
3. **Trust the expertise** - Agents are designed for their specific domains
4. **Iterate quickly** - Agents support the 6-day sprint philosophy

## 🏃 6-Day Sprint Philosophy

The studio operates on aggressive 6-day sprint cycles to maximize learning and minimize waste. Every agent is designed to support this rapid iteration model.

### Why 6-Day Sprints?
- **Fast Feedback**: Get real user data before over-building
- **Momentum**: Ship something meaningful every week
- **Focus**: No time for feature creep or perfectionism
- **Learning**: Fail fast, learn faster, succeed fastest

### Sprint Structure
```
Day 1-2: Planning & Core Implementation
Day 3-4: Integration & Enhancement
Day 5: Testing & Polish
Day 6: Launch Preparation & Documentation
```

### Agent Sprint Principles
1. **Day 1 Deliverables**: Every agent must produce something usable on day one
2. **Iterative Output**: Better to ship 80% today than 100% next sprint
3. **Quick Pivots**: Agents must adapt when data shows a different path
4. **Daily Progress**: Visible progress every single day
5. **Launch Ready**: By day 6, it ships or it's cut

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier
- **description**: When to use the agent with examples
- **color**: Visual identification
- **tools**: Specific tools the agent can access
- **System prompt**: Detailed expertise and instructions

### Adding New Agents

#### Core Requirements
1. Create a new `.md` file in the appropriate department folder
2. Follow the existing format with YAML frontmatter
3. Include 3-4 detailed usage examples
4. Write comprehensive system prompt (500+ words)
5. Test the agent with real tasks

#### 6-Day Sprint Alignment
When creating new agents, ensure they:
- **Can deliver value within 1-2 days** - No agent task should take longer
- **Support iterative development** - Ship incomplete but functional
- **Enable quick wins** - Identify what can ship on day 1
- **Facilitate rapid testing** - Get feedback before perfecting
- **Have clear daily milestones** - Know what "done" means each day

#### Sprint-Optimized Agent Design
- **Bias for action**: Agents should default to doing, not discussing
- **80/20 focus**: Deliver 80% of value with 20% of effort
- **Fail gracefully**: When blocked, pivot rather than stop
- **Document shortcuts**: Track technical debt for future sprints
- **Celebrate progress**: Small wins compound into big victories

## 📊 Agent Performance

Track agent effectiveness through:
- Task completion time
- User satisfaction
- Error rates
- Feature adoption
- Development velocity

## 🚦 Status

- ✅ **Active**: Fully functional and tested
- 🚧 **Coming Soon**: In development
- 🧪 **Beta**: Testing with limited functionality

## 🛠️ Customizing Agents for Your Studio

### Agent Customization Todo List

Use this checklist when creating or modifying agents for your specific needs:

#### 📋 Required Components
- [ ] **YAML Frontmatter**
  - [ ] `name`: Unique agent identifier (kebab-case)
  - [ ] `description`: When to use + 3-4 detailed examples with context/commentary
  - [ ] `color`: Visual identification (e.g., blue, green, purple, indigo)
  - [ ] `tools`: Specific tools the agent can access (Write, Read, MultiEdit, Bash, etc.)

#### 📝 System Prompt Requirements (500+ words)
- [ ] **Agent Identity**: Clear role definition and expertise area
- [ ] **Core Responsibilities**: 5-8 specific primary duties
- [ ] **Domain Expertise**: Technical skills and knowledge areas
- [ ] **Studio Integration**: How agent fits into 6-day sprint workflow
- [ ] **Best Practices**: Specific methodologies and approaches
- [ ] **Constraints**: What the agent should/shouldn't do
- [ ] **Success Metrics**: How to measure agent effectiveness

#### ⏱️ 6-Day Sprint Alignment
- [ ] **Day 1-2 Capabilities**: Agent can deliver initial value within first 2 days
- [ ] **Iterative Outputs**: Supports shipping 80% solutions that can be refined
- [ ] **Quick Pivots**: Can change direction based on early feedback
- [ ] **Daily Deliverables**: Produces tangible progress every single day
- [ ] **Sprint Velocity**: Optimized for speed over perfection
- [ ] **Launch Readiness**: Can prepare features for day 6 deployment
- [ ] **Technical Debt Tracking**: Documents shortcuts for future improvement

#### 🎯 Required Examples by Agent Type

**Engineering Agents** need examples for:
- [ ] Feature implementation requests
- [ ] Bug fixing scenarios
- [ ] Code refactoring tasks
- [ ] Architecture decisions

**Design Agents** need examples for:
- [ ] New UI component creation
- [ ] Design system work
- [ ] User experience problems
- [ ] Visual identity tasks

**Marketing Agents** need examples for:
- [ ] Campaign creation requests
- [ ] Platform-specific content needs
- [ ] Growth opportunity identification
- [ ] Brand positioning tasks

**Product Agents** need examples for:
- [ ] Feature prioritization decisions
- [ ] User feedback analysis
- [ ] Market research requests
- [ ] Strategic planning needs

**Operations Agents** need examples for:
- [ ] Process optimization
- [ ] Tool evaluation
- [ ] Resource management
- [ ] Performance analysis

#### ✅ Testing & Validation Checklist
- [ ] **Trigger Testing**: Agent activates correctly for intended use cases
- [ ] **Tool Access**: Agent can use all specified tools properly
- [ ] **Output Quality**: Responses are helpful and actionable
- [ ] **Edge Cases**: Agent handles unexpected or complex scenarios
- [ ] **Integration**: Works well with other agents in multi-agent workflows
- [ ] **Performance**: Completes tasks within reasonable timeframes
- [ ] **Documentation**: Examples accurately reflect real usage patterns

#### 📅 Sprint Timeline Templates

**Engineering Agents (6-Day Sprint)**
```
Day 1-2: Architecture design, core implementation
Day 3-4: Feature completion, integration
Day 5: Testing, bug fixes, optimization
Day 6: Documentation, deployment preparation
```

**Design Agents (6-Day Sprint)**
```
Day 1: Research, concepts, wireframes
Day 2-3: Design iterations, component creation
Day 4: Developer handoff, design system updates
Day 5: Implementation support, refinements
Day 6: Final polish, asset preparation
```

**Marketing Agents (6-Day Sprint)**
```
Day 1: Market research, strategy development
Day 2-3: Content creation, campaign setup
Day 4-5: Launch execution, monitoring
Day 6: Performance analysis, optimization
```

**Product Agents (6-Day Sprint)**
```
Day 1: Requirements gathering, prioritization
Day 2: Sprint planning, stakeholder alignment
Day 3-4: Feature validation, user testing
Day 5: Iteration based on feedback
Day 6: Release planning, success metrics
```

#### 🔧 Agent File Structure Template

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:
1. **Day 1-2 Focus**: [Initial implementation responsibilities]
2. **Day 3-4 Focus**: [Core feature development]
3. **Day 5 Focus**: [Testing and refinement]
4. **Day 6 Focus**: [Launch preparation]
5. [Additional responsibility]
...

**Sprint Execution Strategy**:
- Day 1: [Specific deliverables]
- Day 2: [Specific deliverables]
- Day 3: [Specific deliverables]
- Day 4: [Specific deliverables]
- Day 5: [Specific deliverables]
- Day 6: [Specific deliverables]

**Quick Win Identification**:
- [What can ship on day 1]
- [What provides immediate value]
- [What validates assumptions fastest]

[Additional detailed system prompt content...]

Your goal is to [ultimate objective]. You believe in shipping fast and learning faster. You understand that done is better than perfect, and that user feedback beats assumptions every time. Remember: in 6-day sprints, momentum is everything—keep shipping, keep learning, keep improving.
```

#### 📂 Department-Specific Guidelines

**Engineering** (`engineering/`): Focus on implementation speed, code quality, testing
**Design** (`design/`): Emphasize user experience, visual consistency, rapid iteration  
**Marketing** (`marketing/`): Target viral potential, platform expertise, growth metrics
**Product** (`product/`): Prioritize user value, data-driven decisions, market fit
**Operations** (`studio-operations/`): Optimize processes, reduce friction, scale systems
**Testing** (`testing/`): Ensure quality, find bottlenecks, validate performance
**Project Management** (`project-management/`): Coordinate teams, ship on time, manage scope

#### 🎨 Customizations

Modify these elements for your needs:
- [ ] Adjust examples to reflect your product types
- [ ] Add specific tools agents have access to
- [ ] Modify success metrics for your KPIs
- [ ] Update department structure if needed
- [ ] Customize agent colors for your brand
- [ ] Align all timelines with your sprint cadence

#### 🚫 Sprint Anti-Patterns to Avoid

When creating or customizing agents, avoid these common mistakes:

**Over-Engineering for 6-Day Sprints**
- ❌ Building perfect solutions that take too long
- ❌ Creating complex architectures for simple problems
- ❌ Waiting for complete requirements before starting
- ✅ Ship 80% solutions and iterate based on feedback

**Perfectionism Blocking Progress**
- ❌ Polishing features that haven't been validated
- ❌ Refactoring before shipping v1
- ❌ Waiting for ideal conditions to launch
- ✅ Launch early, learn fast, improve constantly

**Ignoring Daily Milestones**
- ❌ Working in isolation until day 6
- ❌ No visible progress until the end
- ❌ Saving testing for the last day
- ✅ Show progress daily, test continuously

**Feature Creep**
- ❌ Adding "nice to have" features mid-sprint
- ❌ Expanding scope without cutting elsewhere
- ❌ Building for imaginary users
- ✅ Stay focused on core value, save ideas for next sprint

## 🤝 Contributing

To improve existing agents or suggest new ones:
1. Use the customization checklist above
2. Test thoroughly with real projects
3. Document performance improvements
4. Share successful patterns with the community
